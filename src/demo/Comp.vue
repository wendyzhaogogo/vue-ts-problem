
<template>
  <div></div>
</template>
<script lang="ts">
import { Component, Vue, Prop } from "vue-property-decorator";
@Component
export default class Comp extends Vue {
  mounted() {
    
  }
  created(){

  }
  static notWorkFunc(){
    //anything
  }
}

export function anotherNotWorkFun(){
  //anything
}
</script>