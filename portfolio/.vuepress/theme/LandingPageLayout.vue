<template>
    <Navbar :logo="$site.themeConfig.logo" :sticky="$route.path === '/'" />
</template>

<script>
export default {
  name: "LandingPageLayout"
}
</script>

<style scoped>

</style>