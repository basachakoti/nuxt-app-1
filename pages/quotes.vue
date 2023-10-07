<template>
  <div>
    <div class="card-deck">
        <div class="card" v-for="(quote, index) in quotes" :key="index">
    <div class="card-body">
      <h5 class="card-title">{{ quote }}</h5>
      <p class="card-text">Sri Sadguru Sai Shankar</p>
    </div>
  </div>
  </div>

        
      </div>
</template>
<script>
export default {
  data: () => ({
    quotes: [
      "The rise and fall of your life is as the company you keep.",
      "Be Happy, Make Others Happy, All will be happy, God will be happy.",
      "Service to man is Service to God",
      "Love all... Serve All.",
    ],
  }),
};
</script>
<style>
</style>