<template>
  <div>
    <app-header></app-header>
    <router-view></router-view>
  </div>
</template>

<script>
import addBlog from './components/addBlog'
import showBlogs from './components/showBlogs'
import listBlogs from './components/listBlogs'
import header from './components/header'

export default {

  components: {
    'addBlog': addBlog,
    'showBlogs': showBlogs,
    'listBlogs': listBlogs,
    'app-header': header
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
