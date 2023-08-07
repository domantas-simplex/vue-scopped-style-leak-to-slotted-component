<template>
  <div class="component-with-slot">
    <div>
      Component with Slot
    </div>
    <div>
      Slot starts
    </div>
    <slot></slot>
    <div>
      Slot ends
    </div>
  </div>
</template>

<style scoped>
.component-with-slot {
  width: 500px;
  height: 500px;
  background-color: green;
}
</style>
