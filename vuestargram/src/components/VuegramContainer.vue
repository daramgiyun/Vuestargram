<template>
  <div>
    <VuegramPost :게시물="게시물[i]" v-for="(a,i) in 게시물" :key="i"/>
  </div>
</template>

<script>
import VuegramPost from './VuegramPost.vue';

export default {
  components : {
    VuegramPost,
  },
  props : {
    게시물 : Array,
  }
}
</script>

<style>

</style>