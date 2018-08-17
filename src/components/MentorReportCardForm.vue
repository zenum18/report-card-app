<template>
  <form action="">
    <label for="uName">Username</label>
    <input
      type="text"
      id="uName"
      name="uName"
      placeholder="Username"
      v-model="username"
    />
  </form>
</template>

<script>
export default {
  name: 'MentorReportCardFor',
  data() {
    return {
      username: '',
    };
  },
};
</script>

<style>

</style>
