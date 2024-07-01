<template>
  <nav class="navbar">
    <div class="container">
      <div class="navbar-brand">
        <router-link to="/" class="navbar-item">
          <img src="/logo.png" alt="Logo">
        </router-link>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end">
          <router-link to="/" class="navbar-item">Home</router-link>
          <router-link to="/about" class="navbar-item">About</router-link>
          <router-link to="/resume" class="navbar-item">Resume</router-link>
          <router-link to="/projects" class="navbar-item">Projects</router-link>
          <router-link to="/testimonials" class="navbar-item">Testimonials</router-link>
          <router-link to="/contact" class="navbar-item">Contact</router-link>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'AppNavbar'
};
</script>

<style scoped>
.navbar {
  background-color: black; 
  padding: 1rem 0;
  box-shadow: 0 2px 2px rgba(0, 0, 0, 0.1);
}
.navbar-brand {
  
}
.navbar-menu {
  
}

.navbar-item {
  color: white;
  margin-right: 1rem;
}

</style>




