<template>
  <div>
    <h1>{{ pagetitle }}</h1>
    <p>
      To instant prototype this component, use:
      <code>vue serve MyVueComponent.vue -o</code>
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      pagetitle: "Instant"
    }
  }
}
</script>

<style>

</style>
