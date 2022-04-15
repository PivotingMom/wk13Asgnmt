<template>
  <footer>
    <p>{{footerText}}</p>
  </footer>
</template>

<script>
  export default{
    data(){
      return {
        footerText: 'Copyright &copy; 2022'
      }
    }
  }
</script>
<style scoped>
footer {
  padding: 10px;
  text-align: center;
  background-color: gray;
}
</style>