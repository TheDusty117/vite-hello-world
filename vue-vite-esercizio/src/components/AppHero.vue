<!--TEMPLATE-->
<template>
  <div class="bg-styled">
    {{  description }}
  </div>


</template>

<!--SCRIPT-->
<script>
  export default {
    data() {
      return{
        description: 'ciao sono un hero!'
        
      }
    }
  }
</script>

<!--STYLE-->
<style>

  .bg-styled{
    background-image: url(./img/fotografare-paesaggi.webp);
    background-color: teal;
    height: 500px;
    width: 900px;
    color: wheat;
  }

</style>