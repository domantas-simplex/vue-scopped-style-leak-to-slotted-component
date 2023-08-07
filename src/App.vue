<template>
  <div class="app">
    App
    <ComponentWithSlot>
      <SlottedComponent></SlottedComponent>
    </ComponentWithSlot>
  </div>
</template>

<script setup lang="ts">
import ComponentWithSlot from './components/ComponentWithSlot.vue';
import SlottedComponent from './components/SlottedComponent.vue';

</script>

<style scoped>
.app {
  width: 600px;
  height: 600px;
  background-color: yellow;
}
.repeating-class-name {
  width: 400px;
  height: 400px;
  background-color: red;
}
</style>
