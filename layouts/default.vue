<template>
  <div>
    <nav id="home" role="navigation">
      <div class="nav-wrapper container">
        <NuxtLink to="/" id="logo-container" class="brand-logo">Grúas Behrend</NuxtLink>
        <ul class="right hide-on-med-and-down">
          <li><NuxtLink to="#nosotros">Nosotros</NuxtLink></li>
          <li><NuxtLink to="#servicios">Servicios</NuxtLink></li>
          <li><NuxtLink to="#contactenos">Contáctenos</NuxtLink></li>
        </ul>
        <ul id="nav-mobile" class="sidenav">
          <li><NuxtLink to="#nosotros" class="sidenav-close">Nosotros</NuxtLink></li>
          <li><NuxtLink to="#servicios" class="sidenav-close">Servicios</NuxtLink></li>
          <li><NuxtLink to="#contactenos" class="sidenav-close">Contáctenos</NuxtLink></li>
        </ul>
        <a href="#" data-target="nav-mobile" class="sidenav-trigger">
          <i class="material-icons">menu</i>
        </a>
      </div>
    </nav>

    <div class="carousel carousel-slider center">
      <div class="carousel-fixed-item center hide-on-small-only">
          <div class="row">
            <a href="tel:+56932594273" rel="nofollow">
              <div class="col m10 l8 xl6 offset-m1 offset-l2 offset-xl3 quick-btn hoverable">
                <h2><i class="material-icons small" style="font-size: 2.8rem">phone</i> +569 3259 4273</h2>
              </div>
            </a>
          </div>
        <!-- <a href="tel:+56932594273" rel="nofollow" id="quick-btn" class="btn waves-effect"><i class="material-icons left">phone</i>+569 3259 4273</a> -->
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

    <div class="container">
      <div class="section center hide-on-med-and-up">
        <div class="col s12" style="margin-top: 10px; margin-bottom: 10px;">
          <a href="tel:+56932594273" rel="nofollow">
            <div class="frame center hoverable teal white-text">
              <h4><i class="material-icons small">phone</i> +569 3259 4273</h4>
            </div>
          </a>
        </div>
      </div>
      <div class="divider"></div>
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
              <span class="bold">Teléfono:</span> +569 3259 4273<br>
              <span class="bold">Email:</span> gruasbehrend@gmail.com
            </p>
          </div>
          <div class="col s12 m6 xl4">
            <h6 class="footer-title bold">Enlaces Útiles</h6>
            <ul>
              <li class="valign-wrapper"><i class="tiny material-icons">keyboard_arrow_right</i> <NuxtLink to="#nosotros" class="footer-link">Nosotros</NuxtLink></li>
              <li class="valign-wrapper"><i class="tiny material-icons">keyboard_arrow_right</i> <NuxtLink to="#servicios" class="footer-link">Servicios</NuxtLink></li>
              <li class="valign-wrapper"><i class="tiny material-icons">keyboard_arrow_right</i> <NuxtLink to="#contactenos" class="footer-link">Contáctenos</NuxtLink></li>
            </ul>
          </div>
          <div class="col s12 m12 xl4">
            <h6 class="footer-title bold">Redes Sociales</h6>
            <ul class="social-icons">
              <li>
                <a href="https://www.facebook.com/huevos.carimallin.5" rel="nofollow" target="_blank">
                  <svg fill="#000000" width="32" height="32" version="1.1" id="lni_lni-facebook-original" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 64 64" style="enable-background:new 0 0 64 64;" xml:space="preserve">
                    <path d="M59.5,1h-55C2.5,1,1,2.6,1,4.5v55c0,2,1.6,3.5,3.5,3.5h29.6V38.9h-8v-9.3h8v-6.9c0-8,4.8-12.4,12-12.4c2.4,0,4.8,0.1,7.2,0.4V19h-4.8c-3.8,0-4.6,1.8-4.6,4.5v5.9H53l-1.3,9.4h-8v23.8h15.8c2,0,3.5-1.5,3.5-3.5V4.5C62.9,2.5,61.3,1,59.5,1z"/>
                  </svg>
                </a>
              </li>
              <li>
                <a href="https://www.instagram.com/gruas_behrend/" rel="nofollow" target="_blank">
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
            <div class="col s12"><small> © Copyright <NuxtLink to="/" class="footer-link bold">Grúas Behrend</NuxtLink>. Todos los derechos reservados. Powered by <a class="footer-link bold" href="https://dev-manage.com/" rel="nofollow" target="_blank">Dev-Manage</a>.</small></div>
          </div>
        </div>
        <div class="container show-on-small hide-on-med-and-up center">
          <div class="row">
            <div class="col s12">
              <small>
                © Copyright <NuxtLink to="/" class="footer-link bold">Grúas Behrend</NuxtLink>. Todos los derechos reservados.<br>
                Powered by <a class="footer-link bold" href="https://dev-manage.com/" rel="nofollow" target="_blank">Dev-Manage</a>.
              </small>
            </div>
          </div>
        </div>
      </div>
    </footer>
    <div class="fixed-action-btn">
      <a class="btn-floating btn-large teal">
        <i class="large material-icons">more_vert</i>
      </a>
      <ul>
        <li><a href="mailto:gruasbehrend@gmail.com" rel="nofollow" class="btn-floating red"><i class="material-icons">email</i></a></li>
        <li>
          <a href="https://wa.me/+56932594273" rel="nofollow" class="btn-floating green">
            <svg fill="#ffffff" width="40" height="40" version="1.1" id="lni_lni-whatsapp" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 64 64" style="enable-background:new 0 0 64 64; padding: 0px 7px" xml:space="preserve">
              <g id="WA_Logo">
                <g>
                  <path d="M54,9.9c-5.8-5.8-13.7-9-21.8-9C15.2,0.9,1.3,14.7,1.3,31.7c0,5.5,1.4,10.7,4.1,15.5L1,63.1l16.5-4.2c4.5,2.4,9.6,3.8,14.8,3.8l0,0l0,0C49.2,62.6,63,48.8,63,31.7C63,23.5,59.8,15.8,54,9.9z M32.1,57.4L32.1,57.4c-4.5,0-9.2-1.3-13.1-3.7l-1-0.6l-9.7,2.5l2.7-9.4l-0.6-1c-2.5-4.1-3.9-8.9-3.9-13.7c0-14.1,11.4-25.5,25.6-25.5c6.8,0,13.2,2.7,18,7.5s7.5,11.3,7.5,18.2C57.8,46,46.2,57.4,32.1,57.4z M46.2,38.2c-0.8-0.4-4.5-2.3-5.4-2.4c-0.7-0.3-1.3-0.4-1.7,0.4c-0.4,0.8-2,2.4-2.4,3c-0.4,0.4-0.8,0.6-1.7,0.1c-0.8-0.4-3.2-1.1-6.2-3.9c-2.3-2-3.9-4.5-4.2-5.4c-0.4-0.8-0.1-1.1,0.4-1.6c0.4-0.4,0.8-0.8,1.1-1.4c0.4-0.4,0.4-0.8,0.8-1.3c0.4-0.4,0.1-1-0.1-1.4c-0.3-0.4-1.7-4.2-2.4-5.8c-0.6-1.6-1.3-1.3-1.7-1.3c-0.4,0-1,0-1.4,0s-1.4,0.1-2,1c-0.7,0.8-2.7,2.7-2.7,6.5s2.7,7.3,3.2,8c0.4,0.4,5.5,8.3,13.1,11.7c1.8,0.8,3.2,1.3,4.4,1.7c1.8,0.6,3.5,0.4,4.8,0.3c1.5-0.1,4.5-1.8,5.2-3.7c0.6-1.7,0.6-3.4,0.4-3.7C47.5,38.8,46.9,38.5,46.2,38.2z"/>
                </g>
              </g>
            </svg>
          </a>
        </li>
        <li><a href="tel:+56932594273" rel="nofollow" class="btn-floating blue"><i class="material-icons">phone</i></a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    this.$M.AutoInit();
    var carousel = document.querySelectorAll(".carousel");
    this.$M.Carousel.init(carousel, {
      fullWidth: true,
      indicators: true
    });
    setInterval(() => {
      this.$M.Carousel.getInstance(carousel[0]).next();
    }, 6000);
    var fabtn = document.querySelector('.fixed-action-btn');
    this.$M.FloatingActionButton.init(fabtn, {
      hoverEnabled: false
    });
  }
};
</script>