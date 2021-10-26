<template>
  <div class="container">
    <div id="nosotros" class="section center">
      <div class="row section-content">
        <h3>Nosotros</h3>
        <div class="col s12">
          <h5 class="thin">Somos una empresa líder en la carga, arrastre, enganche de vehículos en Osorno y hacia el exterior.</h5>
        </div>
      </div>
    </div>
    <div class="divider"></div>
    <div id="servicios" class="section center">
      <div class="row section-content">
        <h3>Servicios</h3>
        <div class="col s12 m4">
          <div class="center">
            <i class="large material-icons">flash_on</i>
            <p class="bold">Speeds up development</p>
            <p class="light">We did most of the heavy lifting for you to provide a default stylings that incorporate our custom components.</p>
          </div>
        </div>
        <div class="col s12 m4">
          <div class="center">
            <i class="large material-icons">group</i>
            <p class="bold">User Experience Focused</p>
            <p class="light">By utilizing elements and principles of Material Design, we were able to create a framework that focuses on User Experience.</p>
          </div>
        </div>
        <div class="col s12 m4">
          <div class="center">
            <i class="large material-icons">settings</i>
            <p class="bold">Easy to work with</p>
            <p class="light">We have provided detailed documentation as well as specific code examples to help new users get started.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="divider"></div>
    <div id="agenda" class="section center">
      <div class="row section-content">
        <h3>Agenda</h3>
        <div class="col s12">
          <h5 class="thin">Agenda tú servicio de grúas con nosotros!</h5>
          <form>
            <div class="row">
              <div class="input-field col s12 m6">
                <input id="first_name" type="text" class="validate">
                <label for="first_name">Nombre</label>
              </div>
              <div class="input-field col s12 m6">
                <input id="last_name" type="text" class="validate">
                <label for="last_name">Apellido</label>
              </div>
              <div class="input-field col s12">
                <input id="phone" type="tel" class="validate">
                <label for="phone">Teléfono</label>
              </div>
              <div class="input-field col s12">
                <input id="city" type="text" class="validate">
                <label for="city">Ciudad</label>
              </div>
              <div class="input-field col s12">
                <textarea id="message" class="materialize-textarea"></textarea>
                <label for="message">Mensaje</label>
              </div>
            </div>
            <a class="waves-effect waves-light btn">Enviar</a>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
