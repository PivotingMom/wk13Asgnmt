<template>
  <header>
    <h3>{{ title }}</h3>
    
  </header>
</template>

<script>
export default {
  data(){
    return {
      title: 'spring, 2022'
    }
  }
  }

</script>

<style scoped>
header {
  background-color: brown;
  padding: 10px;
  height: 50px;
  text-align: center;
  color: aliceblue;
}
</style>