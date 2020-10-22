<template>
  <main>
    <section id="main"><app-main /></section>
    <section id="side"><app-side /></section>
  </main>
  <section id="nav"></section>
</template>

<script>
import sidebar from './components/sidebar'
import main from './components/main'
export default {
  components:{
    'app-side' : sidebar,
    'app-main': main,
  }
}
</script>

<style>

</style>