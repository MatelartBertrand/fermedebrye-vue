<template>
  <section>
    <div class="banner-top" :style="`background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url(${loadImage('etable.png')})`">
      <div class="container">
        <div class="row justify-content-center align-items-center">
          <h2 class="text-center">Fermedebrye</h2>
        </div>
        <div class="row justify-content-center align-items-center">
          <h1 class="text-center">Qui fait quoi et pourquoi? </h1>
        </div>

        <br>
      </div>
    </div>

    <div class="container m-t--5">
      <div class="row">
        <div class="col-xs-12 col-md-6 col-lg-3">
          <div class="card-team" :style="`background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url(${loadImage('vincent.jpg')})`">
            <div class="card-category bg-green">0495 46 87 97</div>
            <div class="card-description">
              <h2>Vincent Matelart</h2>
              <p>vincent@fermedebrye.com</p>
              <p>Direction opérationnelle</p>
            </div>
          </div>
          <p class="p-t--2">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
        </div>
        <div class="col-xs-12 col-md-6 col-lg-3">
          <div class="card-team" :style="`background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url(${loadImage('laurence.jpg')})`">
            <div class="card-category bg-green">0474 10 51 44</div>
            <div class="card-description">
              <h2>Laurence Matelart</h2>
              <p>laurence@fermedebrye.com</p>
              <p>Administration et comptabilité</p>
            </div>
          </div>
          <p class="p-t--2">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
        </div>
        <div class="col-xs-12 col-md-6 col-lg-3">
          <div class="card-team" :style="`background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url(${loadImage('nadine.jpg')})`">
            <div class="card-category bg-green">0475 71 89 21</div>
            <div class="card-description">
              <h2>Nadine De Bruyne</h2>
              <p>nadine@fermedebrye.com</p>
              <p>Hivernage Caravane</p>
            </div>
          </div>
          <p class="p-t--2">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
        </div>
        <div class="col-xs-12 col-md-6 col-lg-3">
          <div class="card-team" :style="`background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url(${loadImage('nadine.jpg')})`">
            <div class="card-category bg-green">0477 51 84 05</div>
            <div class="card-description">
              <h2>Pascal Matelart</h2>
              <p>pascal@fermedebrye.com</p>
              <p>Conseil en culture de pomme de terre</p>
            </div>
          </div>
          <p class="p-t--2">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    methods: {
      loadImage (imageName) {
        return require(`~/assets/images/${imageName}`)
      }
    }

  }
</script>
