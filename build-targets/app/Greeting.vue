<template>
  <div>
    <p class="greeting">Hello {{ name }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'RobK'
    }
  },
}
</script>

<style scoped>
  .greeting {
    font-family: sans-serif;
    font-weight: 300;
    font-size: 2rem;
    border: 5px solid lightgreen;
    text-align: center;
    color: blueviolet;
  }
</style>
