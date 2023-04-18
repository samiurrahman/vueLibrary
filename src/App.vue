<template>
  <BrgBlogs :data="data"/>
</template>

<script>
import BrgBlogs from './components/blogs.vue'
  export default {
    data() {
    return {
        data: {
          title: "BRG blogs title",
          paragraph: "this is paragraph",
          etc: "lorem ipsum"
        }
      };
    },
    components: {
      BrgBlogs
    }
  }
</script>
