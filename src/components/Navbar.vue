<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <router-link to="/products" class="navbar-brand">Admin Panel</router-link>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <router-link to="/products" class="navbar-brand">Home<span class="sr-only"></span></router-link>
        </li>
        <li class="nav-item">
          <router-link to="/outstock-list" class="navbar-brand">List Of Product</router-link>
        </li>
      </ul>
    </div>
</nav>
</template>
<script>
export default {
  name: 'Navbar'
}
</script>
