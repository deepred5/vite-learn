<template>
  <h1 @click="count++">hello vite {{count}}</h1>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      count: 0
    }
  }
}
</script>
