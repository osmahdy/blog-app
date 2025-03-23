<template>
  <button
    :style="{ color: color, backgroundColor: background }"
    :url="url"
    @click="openUrl"
  >
    {{ content }}
  </button>
</template>

<script>
export default {
  name: 'base-btn',
  data() {
    return {
      // color: 'blue'
    }
  },
  props: ['content', 'url', 'color', 'background'],
  methods: {
    openUrl() {
      window.open(this.url, '_blank')
    }
  }
}
</script>

<style scoped>
button {
  all: unset;
  padding: 10px;
  border-radius: 15px;
  margin: 10px;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s;
}
button:hover {
  opacity: 0.7;
}
</style>
