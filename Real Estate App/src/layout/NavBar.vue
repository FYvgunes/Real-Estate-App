<script>
export default {
  name: "NavBar"
}
</script>

<template>
  <nav class="navbar navbar-dark  bg-dark fixed-top">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="offcanvas offcanvas-start text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
        <div class="offcanvas-header">
          <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">Emlak Uygulamasi</h5>
          <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
        </div>
        <div class="offcanvas-body">
          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
            <li class="nav-item">
              <RouterLink class="nav-link active" to="/anasayfa">Ana Sayfa </RouterLink>
            </li>
            <li class="nav-link">
              <RouterLink  class="text-decoration-none text-white" to="/randevular">Randevular</RouterLink>
            </li>
            <li class="nav-link ">
              <RouterLink class="text-decoration-none text-white" to="/randevu-olustur">Randevu Olustur </RouterLink>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>

</style>
