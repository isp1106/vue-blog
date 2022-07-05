<template>
  <div>
    <div>
      <router-link to="./detail">11</router-link>
      <h2>{{블로그글[0].title}}</h2>
      <p>{{블로그글[0].date}}</p>
    </div>
    <div>
      <h2>{{블로그글[1].title}}</h2>
      <p>{{블로그글[1].date}}</p>
    </div>
    <div>
      <h2>{{블로그글[2].title}}</h2>
      <p>{{블로그글[2].date}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BlogList',
  props:{
    블로그글 : Array,
  }
}
</script>

<style>

</style>