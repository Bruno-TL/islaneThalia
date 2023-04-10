<template>
  <div class="containerDiv">
    <v-app-bar 
    color="black" 
    class="appBar rounded-be-xl w-100 " 
    height="80" 
    image="../assets/pexels-harry-cooke-6194972.jpg"
    
    >
      <div class="containerDiv-div2 w-75">
        <v-app-bar-title class="text-h4 titulo">Thalia Araujo</v-app-bar-title>
        <h6 class="parag">Designer de sobrancelhas</h6>
      </div>

      <v-img src="../assets/logoTra.png" class="containerDiv-div3" alt=""></v-img>

    </v-app-bar>
  </div>
</template>

<script>

</script>

<style scoped>
.appBar {
  position: fixed !important;
  display: flex;
  justify-content: space-between;
  border: 1px solid rgba(255, 254, 254, 0.534);
}

.containerDiv-div2 {
  display: flex;
  flex-direction: column;
  align-items: start;
  padding-left:20px ;
}

.parag{
  width: 180px;
  text-align: center;
  font-family: 'Exo 2', sans-serif;
  font-size: 14px;
  font-style: italic;
  background: rgba(255, 255, 255, 0.063);
    backdrop-filter: blur( 10px );
    -webkit-backdrop-filter: blur( 13.5px );
    border-radius: 10px;
}

.titulo{
  color: #ffd700;
  text-shadow: black 2px 2px;
  font-family: 'Dancing Script', cursive !important;
}
</style>