<template>
  <section id="side">
      <sidebar-temp />
      <sidebar-stats />
  </section>
</template>

<script>
import sidebar_temp from './sidebar_temp'
import sidebar_stats from './sidebar_stats'
export default {
    components: {
        'sidebar-temp' : sidebar_temp,
        'sidebar-stats' : sidebar_stats,
    },
    props:{}
        
    
}
</script>

<style>

</style>