<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div>
    <div></div>
    <div style="display: flex;flex-direction: column;flex-wrap: wrap; width: 350px;height: 350px;">
      <div style="width: 50px;height: 50px;background-color: brown; margin: 15px;"></div>
      <div style="width: 50px;height: 50px;background-color: brown;margin: 15px;"></div>
      <div style="width: 50px;height: 50px;background-color: brown;margin: 15px;"></div>
      <div style="width: 50px;height: 50px;background-color: brown; margin: 15px;"></div>
      <div style="width: 50px;height: 50px;background-color: brown;margin: 15px;"></div>
      <div style="width: 50px;height: 50px;background-color: brown;margin: 15px;"></div>
      <div style="width: 50px;height: 50px;background-color: brown; margin: 15px;"></div>
      <div style="width: 50px;height: 50px;background-color: brown;margin: 15px;"></div>
      <div style="width: 50px;height: 50px;background-color: brown;margin: 15px;"></div>

    </div>
  </div>
  chama
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
