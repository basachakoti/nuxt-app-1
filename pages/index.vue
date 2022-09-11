<template>
  <div class="h3">
    <!-- <h1>{{ message.message }}</h1> -->
    <h3>Om Sri Sai Ram</h3>
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
