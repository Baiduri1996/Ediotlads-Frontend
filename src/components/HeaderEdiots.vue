<template>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top ">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img src="img/EDIOTLADS..svg" alt="Ediotlads" />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav text-uppercase mx-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Category</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">shop</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">about us</a>
          </li>
        </ul>
        <a class="nav-link text-white" href="#">
          <img src="img/keranjang.svg" alt="keranjang" /> My Cart
          (<span>12</span>)</a
        >
      </div>
    </div>
  </nav>
  <!-- Navbar Akhir -->
</template>

<script>
  export default {
    name: 'HeaderEdiots',
  };
</script>
