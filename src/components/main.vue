<template>
    <section id="main">
        <div class="main-container">
            <div id="title">DRYOUT</div>
        </div>
        <footer>
          <span>&copy; Vikas Saw - 2020</span>
          <i>A</i>
          <i>B</i>
          <i>C</i>
        </footer>
    </section>
</template>

<script>
export default {
    data(){
        return{
        }
    },
    methods:{
    }
}
</script>

<style>
    .main-container{
        height: 90vh;
    }
    footer{
        position: relative;
        padding: 1rem;
        text-align: center;
        background: #000;
        height: 10vh;
    }
    #title{

        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-size: 2.5rem;
    }
</style>