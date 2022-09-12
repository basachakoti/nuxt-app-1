<template>
  <div class="h3">
    <img
      src="~/assets/images/sadgurusaishankar.jpg"
      alt="sadguru sai shankar picture"
    />
    <h3>{{ message }}</h3>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Om Sri Sai Ram",
    };
  },
  // async fetch() {
  // this.message = await fetch("http://laravelsimpleapp-env.eba-n3xeje4c.us-east-1.elasticbeanstalk.com/sairam").then((res) =>
  //   res.json()
  // );
  // },
};
</script>
