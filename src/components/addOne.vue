<template>
  <div>
      <input name="test" v-model="test" />
      <button @click="submit" >click</button>
  </div>
</template>

<script>

export default {
    data(){
        return {
            test: ""
        }
    },
    methods: {
        submit: function() {
            console.log(this.test)
            this.test = ""
        },
        clearIpnut : function () {
            this.test = ""
        }
    }
}
</script>

<style>

</style>