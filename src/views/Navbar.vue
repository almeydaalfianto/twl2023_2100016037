<template>
  <nav class="navbar">
    <ul class="navbar-list">
      <li class="navbar-item"><a href="/DataDisplay" class="navbar-link">Data View</a></li>
      <li class="navbar-item"><a href="/View" class="navbar-link">Data Json</a></li>
      <li class="navbar-item"><a href="/Form" class="navbar-link">Form</a></li>
    </ul>
  </nav>
</template>
  
<style scoped>
.navbar {
  background-color: #EAF2F8;
  color: #333;
  padding: 10px;
}

.navbar-list {
  list-style-type: none;
  display: flex;
  justify-content: space-around;
}

.navbar-item {
  margin: 0 10px;
}

.navbar-link {
  text-decoration: none;
  color: #007BFF;
  font-weight: bold;
}

.navbar-link:hover {
  text-decoration: underline;
}
</style>
