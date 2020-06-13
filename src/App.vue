<template>
  <div>
    <showBlogs></showBlogs>
  </div>
</template>

<script>
import addBlog from './components/addBlog'
import showBlogs from './components/showBlogs'

export default {

  components: {
    'addBlog': addBlog,
    'showBlogs': showBlogs
  },

  data () {
    return {
    }
  }
}
</script>

<style>
  body{
    margin: 0;
    font-family: 'Nunito SemiBold';
  }
</style>
