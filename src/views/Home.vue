<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js dd+ TypeScript App"/>
  </div>
</template>

<script >
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import {web3} from '@/web3/'

export default  {
  components: {
    HelloWorld
  },
  setup(props){

  }
}
</script>
