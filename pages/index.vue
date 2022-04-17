<template>
  <div class="h3">
    {{ message.message }}
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "",
    };
  },
  async fetch() {
    this.message = await fetch("http://laravelsimpleapp-env.eba-n3xeje4c.us-east-1.elasticbeanstalk.com/sairam").then((res) =>
      res.json()
    );
  },
};
</script>
