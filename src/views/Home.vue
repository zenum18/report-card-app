<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Test testString="ROAD TO HIRE REPORT CARD" :testNumber=1 />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import Test from '@/components/Test.vue';

export default {
  name: 'home',
  components: {
    HelloWorld,
    Test,
  },
};
</script>
