<script setup></script>

<template>
  <nav class="navbar navbar-expand-lg bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Laraveller</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ms-auto">
        
          <router-link :to="{name:'home'}" class="nav-link active"  href="#">Home</router-link>
          <router-link :to="{name:'login'}" class="nav-link" href="#">Login</router-link>
          <router-link :to="{name:'register'}" class="nav-link" href="#">Register</router-link>
        
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>
   
    
</style>
