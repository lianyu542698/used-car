<template>
  <div class="hello">
    <p>我是首页</p>
  </div>
</template>

<script>
import http from 'axios'
export default {
  name: 'HelloWorld',
  data () {
    return {
      
    }
  },
  created () {
    http.get('')
    .then((res)=>{
      console.log(res)
      }
    )
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
