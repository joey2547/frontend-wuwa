<script>


</script>

<template>
<nav class="nav nav-pills nav-fill all-caps navbar-custom text-uppercase font-weight-bold">
  <a class="nav-link text-white" href="#">Characters</a>
  <a class="nav-link text-white" href="#">Regions</a>
  <img src="./icons/logo.png" alt="Logo" width="150"  class="d-inline-block align-text-top">
  <a class="nav-link text-white" href="#">events</a>
  <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle text-white" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Join Us
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Login</a></li>
            <li><a class="dropdown-item" href="#">Sign up</a></li>
            <!-- <li><hr class="dropdown-divider"></li> -->
          </ul>
        </li>
</nav>
</template>

<style>
.navbar-custom {
      /* background-image: radial-gradient(circle, #FFFFFF, #04455F); */
      background-color: #052536;
      height: 60px;
      color: #FFFFFF;
      display: flex;
      align-items: center;
}
.nav-link.active {
      /* color: #ffffff;  */
      background-color: #FFFFFF; 
}
.clickable-item {
  padding: 10px;
  border: 1px solid #ccc;
  cursor: pointer;
  transition: border-color 0.3s ease;
}
.outlined {
  border-color: #fff; /* White outline color */
}



</style>