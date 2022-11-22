<template>
  <div>
    <VuegramPost />
    <VuegramPost />
    <VuegramPost />
  </div>
</template>

<script>
import VuegramPost from './VuegramPost.vue';

export default {
  components : {
    VuegramPost,
  },
  props : {
    Posts : Array
  }
}
</script>

<style>

</style>