<script setup></script>

<template>
  <v-carousel hide-delimiters class="my-carousel" height="700px">
    <v-carousel-item
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
      cover
    ></v-carousel-item>
    <v-carousel-item
      src="https://cdn.vuetifyjs.com/images/cards/hotel.jpg"
      cover
    ></v-carousel-item>
    <v-carousel-item
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      cover
    ></v-carousel-item>
  </v-carousel>
</template>

<style>
.my-carousel {
  height: 1700px;
}

v-carousel {
  height: 1700px;
}
</style>
