<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <!-- <Test testString="ROAD TO HIRE REPORT CARD" :testNumber=1 /> -->
    <MentorReportCardForm  />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import MentorReportCardForm from '@/components/MentorReportCardForm.vue';

export default {
  name: 'home',
  components: {
    MentorReportCardForm,
  },
};
</script>
