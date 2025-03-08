<template>
  <div class="page-container">
    <div class="page-content">
      <h1>Welcome to Vue Demo</h1>
      <p>
        This is a simple demonstration of how Vue.js works. Click on the navigation links to see different components 11.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage",
};
</script>

<style scoped>
.page-container {
  background-color: #C4A20A;
  padding: 20px;
}

.page-content {
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0px 4px 16px rgba(0, 0, 0, 0.1);
  text-align: left;
}
</style>
