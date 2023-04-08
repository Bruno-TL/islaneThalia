<template>
  <v-footer class="bg-black text-center d-flex flex-column ">
    <div>
      <v-btn href="https://www.instagram.com/i.thalia__/"  class="mx-4" icon="mdi-instagram" variant="text"></v-btn>
    </div>
    <v-divider></v-divider>

    <div>
      {{ new Date().getFullYear() }} — <strong>Islane Thalia</strong>
    </div>
  </v-footer>
</template>

<script>
  export default {
    data: () => ({
      
    }),
  }
</script>