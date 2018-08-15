<template>
  <div>
    <p> Test String here: {{ testString }}</p>
    <p> Test Number here: {{ testNumber }}</p>
  </div>
</template>

<script>
export default {
  name: 'ReportCard',
  props: {
    testString: String,
    testNumber: Number,
  },
};
</script>

<style>

</style>
