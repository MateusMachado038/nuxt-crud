<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-body-tertiary shadow">
      <div class="container">
        <nuxtLink class="navbar-brand" to="/">Navbar</nuxtLink>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <nuxtLink class="nav-link active" aria-current="page" to="/"
                >Home</nuxtLink
              >
            </li>
            <li class="nav-item">
              <nuxtLink class="nav-link" to="/about-us">About-us</nuxtLink>
            </li>
            <li class="nav-item">
              <nuxtLink class="nav-link" to="/contact-us">Contact-us</nuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script setup></script>

<style></style>
