<template>
  <div>
    my test
    <hello></hello>
  </div>
</template>

<script>
import hello from '@/components/hello.vue'
// import hello from '../../components/hello.vue'
export default {
  name: 'App',
  components: {
    hello
  }
}
</script>

<style>
</style>
