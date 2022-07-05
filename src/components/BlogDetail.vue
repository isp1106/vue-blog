<template>
  <div>
    <h3>상세페이지</h3>
    <h4>{{블로그글[$route.params.id].title}}</h4>
    <p>{{블로그글[$route.params.id].content}}</p>
  </div>
</template>

<script>
export default {
  name: 'BlogDetail',
  props:{
    블로그글 : Array,
  }
}
</script>

<style>

</style>