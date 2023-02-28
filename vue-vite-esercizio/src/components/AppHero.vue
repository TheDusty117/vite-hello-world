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
    background-color: teal;
    height: 400;
    width: 900px;
    color: wheat;
  }

</style>