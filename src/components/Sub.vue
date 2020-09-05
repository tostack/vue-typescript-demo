<template>
  <button @click="sayHello">hello</button>  
</template>

<script lang="ts">
import {Component, Vue} from 'vue-property-decorator'
@Component
export default class Sub extends Vue{
  // private name:string = '111'
  private sayHello(){
    console.log(111)
  }
}
</script>

<style>

</style>