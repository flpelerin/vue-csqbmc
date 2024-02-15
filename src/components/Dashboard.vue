<template>
<div class="dashboard">
  <h1>Dashboard</h1>
  <ul>
    <li><router-link to="/link1">Link 1</router-link></li>
    <li><router-link to="/link2">Link 2</router-link></li>
    <li><router-link to="/link3">Link 3</router-link></li>
    <li><router-link to="/link4">Link 4</router-link></li>
  </ul>
  <router-view></router-view>
</div>
</template>

<script>
export default {
name: 'Dashboard',
};
</script>

<style scoped>
/* Add your custom styling here */
</style>
