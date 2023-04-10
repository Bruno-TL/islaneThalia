<template>
  <v-overlay v-model="overlay" contained class="promoAlert">
    <v-progress-linear indeterminate color="orange-accent-4" class="w-75" rounded height="6"></v-progress-linear>
    <div class="container1">
      <img src="../assets/promoAlert/promoMOd.png" alt="">
    </div>

    <div class="container2">
      <v-btn color="red-accent-4" @click="overlay = false">
        Fechar
      </v-btn>
      <v-btn color="orange-accent-4" @click="overlay = false"
        href="https://api.whatsapp.com/send?phone=5585992209399&text=OI,%20queria%20saber%20mais%20sobre%20os%20seus%20servi%C3%A7os.">
        Falar com a Thalia
        <v-icon size="x-large" color="orange-lighten-5" icon="mdi-whatsapp" end></v-icon>
      </v-btn>
    </div>

  </v-overlay>
</template>

<script>
export default {
  data: () => ({
    overlay: true,
  }),
}
</script>

<style scoped>
.promoAlert {
  /* position: fixed; */
  display: flex;
  justify-content: center;
  margin-top: 80px;
  padding-top: 50px;
}

.container1 {
  display: flex;
  justify-content: center;
}

.container2 {
  display: flex;
  justify-content: space-around;
  position: absolute;
  top: 95%;
  left: 19%;
  width: 60%;
}

img {
  width: 200%;
}

@media (max-width: 769px) {
  img {
    width: 80%;
  }

  .container2 {
    display: flex;
    justify-content: space-around;
    position: absolute;
    top: 95%;
    left: 10%;
    width: 80%;
  }
}
</style>
