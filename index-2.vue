<script>
export default {
  /**
   * A description of the entire function.
   *
   * @return {Object} An object containing the data properties for the component.
   */
  data() {
    return {
      list: [
        /* ... */
      ]
    }
  },
  mounted() {
    console.log(this.$refs.items)
  }
}
</script>

<template>
  <ul>
    <li v-for="item in list" ref="items">
      {{ item }}
    </li>
  </ul>
</template>