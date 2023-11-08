<script lang="ts">
    export default {
        name : "Navbar"
    }
</script>
<template>
   <header>
    <div class="wrapper">
      <nav class="navbar">
        <RouterLink to="/" style="margin-left: 1rem;">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>       
</template>
<style scoped>
nav {
  display: flex;
  align-items: center; 
  justify-content: start; 
  gap: 1rem;
  height: 2rem;
}

/* Barra de Navegação */
.navbar {
    background-color: #333333;
    color: #FFFFFF;
}

.navbar a {
    color: #FFFFFF;
    text-decoration: none;
}

.navbar a:hover {
    color: #FFD700; /* Cor de destaque ao passar o mouse */
}
</style>