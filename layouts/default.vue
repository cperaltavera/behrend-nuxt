<template>
  <div>
    <nav role="navigation">
      <div class="nav-wrapper container">
        <NuxtLink to="/" id="logo-container" class="brand-logo">Logo</NuxtLink>
        <ul class="right hide-on-med-and-down">
          <li><NuxtLink to="/">Nosotros</NuxtLink></li>
          <li><NuxtLink to="/1">Servicios</NuxtLink></li>
          <li><NuxtLink to="/2">Agenda</NuxtLink></li>
        </ul>
        <ul id="nav-mobile" class="sidenav">
          <li><NuxtLink to="/">Nosotros</NuxtLink></li>
          <li><NuxtLink to="/1">Servicios</NuxtLink></li>
          <li><NuxtLink to="/2">Agenda</NuxtLink></li>
        </ul>
        <a href="#" data-target="nav-mobile" class="sidenav-trigger">
          <i class="material-icons">menu</i>
        </a>
      </div>
    </nav>

    <div class="carousel carousel-slider center">
      <div class="carousel-fixed-item center">
        <a class="btn waves-effect white grey-text darken-text-2"><i class="material-icons left">phone</i>+569 3259 4273</a>
      </div>
      <div class="carousel-item red white-text" href="#one!">
        <h2>First Panel</h2>
        <p class="white-text">This is your first panel</p>
      </div>
      <div class="carousel-item amber white-text" href="#two!">
        <h2>Second Panel</h2>
        <p class="white-text">This is your second panel</p>
      </div>
      <div class="carousel-item green white-text" href="#three!">
        <h2>Third Panel</h2>
        <p class="white-text">This is your third panel</p>
      </div>
      <div class="carousel-item blue white-text" href="#four!">
        <h2>Fourth Panel</h2>
        <p class="white-text">This is your fourth panel</p>
      </div>
    </div>

    <Nuxt />

    <footer class="page-footer">
      <div class="container">
        <div class="row">
          <div class="col l6 s12">
            <h5 class="footer-title">Store Bio</h5>
            <p class="footer-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras
              interdum congue ante, eu ultrices eros finibus ut. Donec libero
              ligula, varius tincidunt metus non, aliquet faucibus purus.
              Vivamus eleifend ligula metus, eget cursus quam iaculis vel. Donec
              enim lacus, scelerisque nec consequat eu, dapibus in augue.
            </p>
          </div>
          <div class="col l3 s12">
            <h5 class="footer-title">Site Links</h5>
            <ul>
              <li><NuxtLink to="/" class="footer-link">Home</NuxtLink></li>
              <li><NuxtLink to="/products" class="footer-link">Products</NuxtLink></li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer-copyright">
        <div class="container">© Copyright <a class="footer-link" href="#">Grúas Behrend</a>. Todos los derechos reservados. Powered by <a class="footer-link" href="#">Dev-Manage</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  mounted() {
    this.$M.AutoInit();
    var elems = document.querySelectorAll(".carousel");
    this.$M.Carousel.init(elems, {
      fullWidth: true,
      indicators: true
    });
    // setInterval(() => {
    //   this.$M.Carousel.getInstance(elems[0]).next();
    // }, 6000);
  }
};
</script>