<template>
  <c-theme-provider>
    <c-reset />
    <router-view />
  </c-theme-provider>
</template>

<style>
  html {
    height: 100%;
  }
  body {
    height: 100%;
  }
</style>
<script>
export default {
  name: "App",
};
</script>
