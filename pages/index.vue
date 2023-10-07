<template>
  <div class="p-2">
    <div class="card p-2 sadguru-photo" style="width: 18rem">
      <img src="~/assets/images/sai.jpg" alt="sadguru sai shankar picture" />
      <p class="m-0 sai-message">Sri Sadguru Sai Shankar</p>
      <div class="card-title font-weight-bold h5">Message</div>
      <h6>{{ message }}</h6>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Be happy, Make others happy, All will be happy, God will be happy",
    };
  },
  // async fetch() {
  // this.message = await fetch("http://laravelsimpleapp-env.eba-n3xeje4c.us-east-1.elasticbeanstalk.com/sairam").then((res) =>
  //   res.json()
  // );
  // },
};
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Ms+Madi&display=swap");

.sai-message {
  font-family: "Ms Madi", cursive;
  font-size: 1.5rem;
  text-align: center;
  font-weight: bold;
}

.sadguru-photo {
  background: #f1f1f1 !important;
}
</style>