<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarTogglerDemo03"
      aria-controls="navbarTogglerDemo03"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <i class="cil-mood-very-good"></i>
    <a class="navbar-brand" href="/">memesbd</a>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search" />
      <button class="btn btn-outline-success my-2 my-sm-0 px-4" type="submit">Search</button>
    </form>

    <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
      <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
        <li class="nav-item px-2">
          <a class="nav-link" href="#">
            Home
            <span class="sr-only">(current)</span>
          </a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Upload a Meme</a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">My Posts</a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">My Pending Posts</a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">link</a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Logout</a>
        </li>

        <li class="nav-item px-2">
          <a class="nav-link" href="#">Login/Register</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    @import url("https://unpkg.com/@coreui/coreui@3.0.0-rc.0/dist/css/coreui.min.css");
    @import url("https://unpkg.com/@coreui/icons@1.0.0/css/all.min.css");
    @import url("https://unpkg.com/@coreui/icons@1.0.0/css/free.min.css");
    @import url("https://unpkg.com/@coreui/icons@1.0.0/css/brand.min.css");
    @import url("https://unpkg.com/@coreui/icons@1.0.0/css/flag.min.css");

</style>