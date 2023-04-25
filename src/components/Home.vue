<template>
  <v-container class="fill-height">
    <v-responsive class="d-flex align-center text-center fill-height">
      
      <v-row class="align-center">
        <v-spacer></v-spacer>
        <v-col cols="6">
          <MWLogo></MWLogo>
        </v-col>
        <v-spacer></v-spacer>
      </v-row>

      <v-row class="align-center">
        <v-col cols="12" style="font-size: 2em; font-family: Neucha; color: primary;">
          Hi there! My name is Molly Whitener.
          <br>
          I love to create, think, and problem-solve.
        </v-col>
      </v-row>

      <div class="py-14" />

    </v-responsive>
  </v-container>
</template>

<script lang="ts" setup>
  import MWLogo from './MWLogo.vue';
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Neucha&display=swap');

</style>
