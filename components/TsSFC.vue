<template>
  <div>result: {{ result }}</div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  data: () => ({
    a: 1,
    b: 2,
  }),
  computed: {
    result() {
      return this.add(this.a, this.b)
    },
  },
  methods: {
    add(a, b) {
      return a + b
    },
  },
})
</script>
