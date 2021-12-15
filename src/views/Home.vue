<template>
  <div></div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  created() {
    console.log(this.$route.params.projectId);
  }
};
</script>
