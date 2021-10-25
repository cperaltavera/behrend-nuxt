<template>
  <div>
    <nav role="navigation">
      <div class="nav-wrapper container">
        <NuxtLink to="/" id="logo-container" class="brand-logo">Grúas Behrend</NuxtLink>
        <ul class="right hide-on-med-and-down">
          <li><a href="#nosotros">Nosotros</a></li>
          <li><a href="#servicios">Servicios</a></li>
          <li><a href="#agenda">Agenda</a></li>
        </ul>
        <ul id="nav-mobile" class="sidenav">
          <li><a href="#nosotros">Nosotros</a></li>
          <li><a href="#servicios">Servicios</a></li>
          <li><a href="#agenda">Agenda</a></li>
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
      <div class="carousel-item" href="#one!">
        <img src="../assets/images/01.jpg">
      </div>
      <div class="carousel-item white-text" href="#two!">
        <img src="../assets/images/02.jpg">
      </div>
      <div class="carousel-item white-text" href="#three!">
        <img src="../assets/images/03.jpg">
      </div>
      <div class="carousel-item white-text" href="#four!">
        <img src="../assets/images/04.jpg">
      </div>
    </div>

    <Nuxt />

    <footer class="page-footer">
      <div class="container">
        <div class="row">
          <div class="col s12 m6 xl4">
            <h6 class="footer-title bold">Grúas Behrend</h6>
            <p>
              Dirección<br>
              Osorno, Región de Los Lagos<br>
              Chile<br><br>
              <span class="bold">Teléfono:</span> +56 9 5611 5391<br>
              <span class="bold">Email:</span> contacto@dev-manage.com
            </p>
          </div>
          <div class="col s12 m6 xl4">
            <h6 class="footer-title bold">Enlaces Útiles</h6>
            <ul>
              <li class="valign-wrapper"><i class="tiny material-icons">keyboard_arrow_right</i> <NuxtLink to="/" class="footer-link">Nosotros</NuxtLink></li>
              <li class="valign-wrapper"><i class="tiny material-icons">keyboard_arrow_right</i> <NuxtLink to="/1" class="footer-link">Servicios</NuxtLink></li>
              <li class="valign-wrapper"><i class="tiny material-icons">keyboard_arrow_right</i> <NuxtLink to="/2" class="footer-link">Agenda</NuxtLink></li>
            </ul>
          </div>
          <div class="col s12 m12 xl4">
            <h6 class="footer-title bold">Redes Sociales</h6>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras interdum congue ante, eu ultrices eros finibus ut. Donec libero ligula, varius tincidunt metus non, aliquet faucibus purus. Vivamus eleifend ligula metus, eget cursus quam iaculis vel. Donec enim lacus, scelerisque nec consequat eu, dapibus in augue.</p>
          </div>
        </div>
      </div>
      <div class="footer-copyright">
        <div class="container show-on-medium-and-up hide-on-small-only">
          <div class="row">
            <div class="col s12"><small> © Copyright <a class="footer-link bold" href="#">Grúas Behrend</a>. Todos los derechos reservados. Powered by <a class="footer-link bold" href="#">Dev-Manage</a>.</small></div>
          </div>
        </div>
        <div class="container show-on-small hide-on-med-and-up center">
          <div class="row">
            <div class="col s12">
              <small>
                © Copyright <a class="footer-link bold" href="#">Grúas Behrend</a>. Todos los derechos reservados.<br>
                Powered by <a class="footer-link bold" href="#">Dev-Manage</a>.
              </small>
            </div>
          </div>
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
    setInterval(() => {
      this.$M.Carousel.getInstance(elems[0]).next();
    }, 6000);
  }
};
</script>