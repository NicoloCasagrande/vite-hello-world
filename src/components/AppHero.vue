<script>
  export default{
    data(){
      return {
        title: 'Titolo hero', 
        hero: 'Questa è una hero di esempio con del testo casuale'
      }
    }
  }
</script>

<template>
    <div class="container">
        <h2>{{ title }}</h2>
        <p>{{ hero }}</p>
    </div>
</template>

<style scoped>
h2{
  color: black;
}
.container{
    margin: auto;
}
</style>