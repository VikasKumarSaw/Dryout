<template>
    <main>
      <app-nav />
      <app-main />
      <app-side />
    </main>
</template>

<script>
import sidebar from './components/sidebar'
import main from './components/main'
import sidenav from './components/sidenav'
export default {
  components:{
    'app-side' : sidebar,
    'app-main': main,
    'app-nav': sidenav,
  },
  data(){
    return{
    }
  },
  methods:{

  }
}
</script>

<style>

</style>