<template>
  <div class="hello">
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
    

  },
  created() {
    let arr = [1,2,3,4,5,6,1,2,3]
    arr.splice(0,3)
    console.log(arr);
  },
  methods: {
    one(){
      
    }
  },
}
</script >

<style lang="less">
</style>
186 6942 4516