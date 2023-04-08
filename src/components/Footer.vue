<template>
  <v-footer class="bg-black text-center d-flex flex-column ">
    <div>
      <v-btn v-for="icon in icons" :key="icon" class="mx-4" :icon="icon" variant="text"></v-btn>
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
      icons: [
        'mdi-facebook',
        'mdi-linkedin',
        'mdi-instagram',
      ],
    }),
  }
</script>