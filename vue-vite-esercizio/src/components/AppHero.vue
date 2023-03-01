<template>
  <div class="bg-styled">
    {{  description }}
  </div>


</template>

<script>
  export default {
    data() {
      return{
        description: 'ciao sono un hero!'
        
      }
    }
  }
</script>

<style>

  .bg-styled{
    background-image: url(./img/fotografare-paesaggi.webp);
    background-color: teal;
    height: 500px;
    width: 900px;
    color: wheat;
  }

</style>