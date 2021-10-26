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
            <a class="btn waves-effect white grey-text darken-text-2"><i class="material-icons left">phone</i>+569 3259 4273</a>
             <a class="btn waves-effect white grey-text darken-text-2"><i class="material-icons left">phone</i>+569 3259 4273</a>
           <a class="btn waves-effect white grey-text darken-text-2"><i class="material-icons left">phone</i>+569 3259 4273</a>
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
              <li class="valign-wrapper"><i class="tiny material-icons">keyboard_arrow_right</i> <a href="#nosotros" class="footer-link">Nosotros</a></li>
              <li class="valign-wrapper"><i class="tiny material-icons">keyboard_arrow_right</i> <a href="#servicios" class="footer-link">Servicios</a></li>
              <li class="valign-wrapper"><i class="tiny material-icons">keyboard_arrow_right</i> <a href="#agenda" class="footer-link">Agenda</a></li>
            </ul>
          </div>
          <div class="col s12 m12 xl4">
            <h6 class="footer-title bold">Redes Sociales</h6>
            <ul class="social-icons">
              <li>
                <a href="https://facebook.com" target="_blank">
                  <svg fill="#000000" width="32" height="32" version="1.1" id="lni_lni-facebook-original" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 64 64" style="enable-background:new 0 0 64 64;" xml:space="preserve">
                    <path d="M59.5,1h-55C2.5,1,1,2.6,1,4.5v55c0,2,1.6,3.5,3.5,3.5h29.6V38.9h-8v-9.3h8v-6.9c0-8,4.8-12.4,12-12.4c2.4,0,4.8,0.1,7.2,0.4V19h-4.8c-3.8,0-4.6,1.8-4.6,4.5v5.9H53l-1.3,9.4h-8v23.8h15.8c2,0,3.5-1.5,3.5-3.5V4.5C62.9,2.5,61.3,1,59.5,1z"/>
                  </svg>
                </a>
              </li>
              <li>
                <a href="https://instagram.com" target="_blank">
                  <svg fill="#000000" width="32" height="32" version="1.1" id="lni_lni-instagram-original" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 64 64" style="enable-background:new 0 0 64 64;" xml:space="preserve">
                    <g>
	                  <path d="M62.9,19.2c-0.1-3.2-0.7-5.5-1.4-7.6S59.7,7.8,58,6.1s-3.4-2.7-5.4-3.5c-2-0.8-4.2-1.3-7.6-1.4C41.5,1,40.5,1,32,1s-9.4,0-12.8,0.1s-5.5,0.7-7.6,1.4S7.8,4.4,6.1,6.1s-2.8,3.4-3.5,5.5c-0.8,2-1.3,4.2-1.4,7.6S1,23.5,1,32s0,9.4,0.1,12.8c0.1,3.4,0.7,5.5,1.4,7.6c0.7,2.1,1.8,3.8,3.5,5.5s3.5,2.8,5.5,3.5c2,0.7,4.2,1.3,7.6,1.4C22.5,63,23.4,63,31.9,63s9.4,0,12.8-0.1s5.5-0.7,7.6-1.4c2.1-0.7,3.8-1.8,5.5-3.5s2.8-3.5,3.5-5.5c0.7-2,1.3-4.2,1.4-7.6c0.1-3.2,0.1-4.2,0.1-12.7S63,22.6,62.9,19.2zM57.3,44.5c-0.1,3-0.7,4.6-1.1,5.8c-0.6,1.4-1.3,2.5-2.4,3.5c-1.1,1.1-2.1,1.7-3.5,2.4c-1.1,0.4-2.7,1-5.8,1.1c-3.2,0-4.2,0-12.4,0s-9.3,0-12.5-0.1c-3-0.1-4.6-0.7-5.8-1.1c-1.4-0.6-2.5-1.3-3.5-2.4c-1.1-1.1-1.7-2.1-2.4-3.5c-0.4-1.1-1-2.7-1.1-5.8c0-3.1,0-4.1,0-12.4s0-9.3,0.1-12.5c0.1-3,0.7-4.6,1.1-5.8c0.6-1.4,1.3-2.5,2.3-3.5c1.1-1.1,2.1-1.7,3.5-2.3c1.1-0.4,2.7-1,5.8-1.1c3.2-0.1,4.2-0.1,12.5-0.1s9.3,0,12.5,0.1c3,0.1,4.6,0.7,5.8,1.1c1.4,0.6,2.5,1.3,3.5,2.3c1.1,1.1,1.7,2.1,2.4,3.5c0.4,1.1,1,2.7,1.1,5.8c0.1,3.2,0.1,4.2,0.1,12.5S57.4,41.3,57.3,44.5z"/>
	                  <path d="M32,16.1c-8.9,0-15.9,7.2-15.9,15.9c0,8.9,7.2,15.9,15.9,15.9S48,40.9,48,32S40.9,16.1,32,16.1z M32,42.4c-5.8,0-10.4-4.7-10.4-10.4S26.3,21.6,32,21.6c5.8,0,10.4,4.6,10.4,10.4S37.8,42.4,32,42.4z"/>
	                  <ellipse cx="48.7" cy="15.4" rx="3.7" ry="3.7"/>
                    </g>
                  </svg>
                </a>
              </li>
            </ul>
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