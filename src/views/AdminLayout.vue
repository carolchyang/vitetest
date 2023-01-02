<template>
  <nav class="navbar navbar-expand-lg bg-light">
    <div class="container-fluid">
      <RouterLink to="/admin/productsmanage" class="navbar-brand">Admin Navbar</RouterLink>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <RouterLink to="/admin/productsmanage" class="nav-link active"
              >Admin-products</RouterLink
            >
          </li>
          <li class="nav-item">
            <RouterLink to="/admin/usersmanage" class="nav-link">Admin-users</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink to="/" class="nav-link">去前台</RouterLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <hr />
  <RouterView />
</template>

<script setup>
import 'bootstrap/js/dist/collapse';
</script>
