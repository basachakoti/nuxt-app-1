<template>
  <div class="h3" style="background: rgb(255, 218, 107); padding: 8px">
    <div class="head text-center">
      <img
        src="~/assets/images/sadgurusaishankar.jpg"
        alt="sadguru sai shankar picture"
      />
      <h3>{{ message }}</h3>
      <v-card class="bg-transparent shadow-none">
        <v-container>
          <v-row dense>
            <v-col v-for="card in cards" :key="card.title" :cols="card.flex">
              <NuxtLink :to="card.link">
                <v-card>
                  <v-img
                    :src="card.src"
                    class="white--text align-end"
                    gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                    height="200px"
                  >
                  </v-img>
                  <v-card-title v-text="card.title"></v-card-title>
                </v-card>
              </NuxtLink>
            </v-col>
          </v-row>
        </v-container>
      </v-card>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Om Sri Sai Ram",
      cards: [
        {
          title: "Sai Leela - Stories",
          src: "https://cdn.vuetifyjs.com/images/cards/house.jpg",
          flex: 3,
          link: "/stories",
        },
        {
          title: "Sai Vaani - Quotations",
          src: "https://cdn.vuetifyjs.com/images/cards/road.jpg",
          flex: 3,
          link: "/quotes",
        },
        {
          title: "Sai Bhajans",
          src: "https://cdn.vuetifyjs.com/images/cards/plane.jpg",
          flex: 3,
          link: "/bhajans",
        },
      ],
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
/* .head { */
/* background: transparent; */
/* } */
.head {
  /* width: 100%; */
  /* height: 56.25%; */
  aspect-ratio: 3/2;
  background-image: url("~assets/images/pattern.png");
  background-color: #7e8446;
  background-repeat: repeat;
}
</style>