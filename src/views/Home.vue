<template>
  <div class="home">
    <Header msg="Welcome to Your Vue.js App"/>
    <Search/>
    <Main/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Search from '@/components/Search.vue'
import Main from '@/components/Main.vue'


export default {
  name: 'home',
  components: {
    Header,
    Search,
    Main
  }
}
</script>
