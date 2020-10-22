<template>
    <main>
      <app-main />
      <app-side />
    </main>
</template>

<script>
import sidebar from './components/sidebar'
import main from './components/main'
export default {
  components:{
    'app-side' : sidebar,
    'app-main': main,
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