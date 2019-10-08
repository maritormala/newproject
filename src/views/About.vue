<template>
  <div class="about">
    <h1>Whoop! {{name}}
    </h1>
  </div>
</template>
<script>
export default {
  data: ()=> ({
    name: "anna", 
    age: 1,
  })
}
</script>
<style scoped>
h1 {
  color:red;
} 
</style>