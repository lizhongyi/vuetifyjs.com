<template>
  <v-card>
    <v-card-text>
      <v-slider v-model="value1" dark thumb-label step="2"></v-slider>
      <v-slider v-model="value2" dark disabled></v-slider>
    </v-card-text>
  </v-card>
</template>

<script>
  export default {
    data () {
      return {
        value1: 0,
        value2: 0
      }
    }
  }
</script>
