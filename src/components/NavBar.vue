<template>
  <nav class="navbar navbar-expand-lg bg-transparent">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse mt-4" id="navbarTogglerDemo01">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0 mx-auto">
        <li class="nav-item">
            <router-link to="/">Home</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/about">About</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/products">Products</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/admin">Admin</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/login">Login</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
    export default {
        name: 'NavBar'
    }
</script>

<style scoped>
nav {
    font-family: monospace;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
    text-decoration: none;
    color: black;
    box-shadow: inset 0 0 0 0 black;
    padding: 0 .25rem;
    margin: 0 -.25rem;
    transition: color .7s ease-in-out, box-shadow .3s ease-in-out;
    border-radius: 5px;
    font-size: 19px;
}
a:hover {
    color: greenyellow;
    box-shadow: inset 200px 0 0 0 black;;
    border-radius: 5px;
}

</style>