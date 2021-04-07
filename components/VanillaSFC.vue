<template>
  <div>result: {{ result }}</div>
</template>

<script>
export default {
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
}
</script>
