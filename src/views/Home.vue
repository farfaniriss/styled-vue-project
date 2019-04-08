<template>
  <div class="main-container">
    <h1>Container</h1>
    <div class="main-component">
      <div class="container-row">
        Label 1
        <input type="text" v-model="label1" placeholder="label 1">
      </div>
      <div class="container-row">
        Label 2
        <input type="text" v-model="label2" placeholder="label 2">
      </div>
      <div class="container-row">
        Label 3
        <input type="text" v-model="label3" placeholder="label 3">
      </div>
      <div class="container-row">
        <button type="button" class="btn-primary">Primary</button>
        <button type="button" class="btn-secondary">Secondary</button>
        <button type="button" class="btn-danger">Danger</button>
      </div>
      <div class="container-row">
        <button type="button" class="btn-outline-primary">Outline primary</button>
        <button type="button" class="btn-outline-danger">Outline danger</button>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Component({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {
  label1 = "";
  label2 = "";
  label3 = "";
}
</script>
