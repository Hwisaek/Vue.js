<template>
  <input id="calendar" />
</template>

<script>
export default {
  mounted() {
    $("#calendar").datepicker();
  },
};
</script>

<style>
</style>