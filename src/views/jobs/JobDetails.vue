<template>
<div>
  <h1>{{title}}</h1>
  <p>
  the jod id is : {{id}}
  </p>
  <p>{{details}}</p>
</div>
</template>

<script>
export default {
    props:['id', 'title', 'details'],
// data(){
//     return{
//         id: this.$route.params.id
//     }
// }
}
</script>

<style>

</style>