<template>
  <section>
    <section class="banner-homepage" style="background-image: linear-gradient(-225deg, rgba(0,0,0,0.6) 0%, rgba(0,0,0,0.5) 50%), url('https://images.pexels.com/photos/296230/pexels-photo-296230.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260');">
      <div class="container">
        <div class="row justify-content-center align-items-center">
          <h2>Fermedebrye</h2>
        </div>
        <div class="row justify-content-center align-items-center">
          <h1>Travail de qualité</h1>
        </div>
        <br>
        <div class="row justify-content-center align-items-center">
          <p>Exploitation agricole en plein changement</p>
        </div>
        <br>
      </div>
    </section>

    <!-- CTA -->
    <div class="container">
      <div class="m-tb--5">
        <div class="row justify-content-center align-items-center">
          <div class="col-xs-12 col-md-8 col-md-offset-2">
            <div class="container-fluid">
              <div class="row">
                <div class="col-xs-12 col-sm-6">
                  <nuxt-link class="" to="/caravane"><button class="btn btn-black btn-fluid">Hivernage de votre caravane</button></nuxt-link>
                </div>
                <div class="col-xs-12 col-sm-6">
                  <nuxt-link class="" to="/luzerne"><button class="btn btn-green btn-fluid">Pourquoi la luzerne</button></nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <h2 class="section-title-home m-tb--3" style="font-size:30px;">
        <div class="section-title-home-content" style="background-color: white;">
          Notre philosophie de travaille
        </div>
      </h2>
      <div class="p-tb--3">
        <div class="fdb-why-vincent">
          <div class="row justify-content-center align-items-center">
            <div class="col-xs-12 col-md-3 col-md-offset-1">
              <div class="image m-b--1">
                <img src="~assets/images/vincent.jpg" class="linear-gradient">
              </div>
            </div>
            <div class="col-xs-12 col-md-5">
              <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
            </div>
          </div>
        </div>
      </div>
    </div>


    <!-- activity  -->
    <section class="wrapper-bg-gray">
      <div class="container">
        <h2 class="section-title-home" style="font-size:30px;">
          <div class="section-title-home-content" style="background-color: white;">
            Nos différentes activités
          </div>
        </h2>
        <div class="p-tb--3">
          <div class="fdb-activity">
            <div class="row">
              <div class="col-xs-12 col-md-6">
                <div class="image m-b--1">
                  <img src="~assets/images/banner-andainage.png" class="linear-gradient">
                </div>
              </div>
              <div class="col-xs-12 col-md-6">
                <h3 class="m-b--1">Culture de luzerne</h3>
                <p class="margin-top-20px">La culture de luzerne est quelque chose de fantastique. D'un point de vue cultural, elle enrichit le sol en azote, favorise la faune et la flore du sol et lutte contre les adventices de manière totalement naturelle.
                <br><br>
                D'un point de vue nutrition animale, bien que malheureusement peu connue et utilisée en Belgique, la luzerne est premièrement LE fourrage santé pour le bétail. En plus de cela, elle fournit naturellement un riche taux en protéine permettant de respecter un cahier des charge de production locale.</p>
                <nuxt-link class="m-t--1" to="/luzerne"><button class="btn btn-black m-t--1">En savoir plus</button></nuxt-link>
              </div>
            </div>
          </div>
        </div>

        <div class="p-tb--3">
          <div class="fdb-activity">
            <div class="row">
              <div class="col-xs-12 col-md-6">
                <div class="image m-b--1">
                  <img src="~assets/images/caravanes.png" class="linear-gradient">
                </div>
              </div>
              <div class="col-xs-12 col-md-6">
                <h3 class="m-b--1">Hivernage caravane</h3>
                <p class="margin-top-20px">
                Suite à la disponibilité d'un vaste bâtiment couvert, nous nous sommes orientés vers l'hivernage de caravanes.
                <br><br>
                Nous proposons un service de qualité, dans une relation de confiance, avec un bâtiment sécurisé à destination des personnes souhaitant dormir sur le deux oreilles le restant de l'année.
                <br><br>
                Un seul mot : On s'occupe de tout. Vous nous déposez votre véhicule. Quand vous en avez besoin, vous le récupérez propre, entretenu, prêt à partir vers de nouveaux horizons.
                </p>
                <nuxt-link class="m-t--1" to="/caravane"><button class="btn btn-black m-t--1">En savoir plus</button></nuxt-link>
              </div>
            </div>
          </div>
        </div>

        <div class="p-tb--3">
          <div class="fdb-activity">
            <div class="row">
              <div class="col-xs-12 col-md-6">
                <div class="image m-b--1">
                  <img src="~assets/images/carotte-recolte2.png" class="linear-gradient">
                </div>
              </div>
              <div class="col-xs-12 col-md-6">
                <h3 class="m-b--1">Culture Biologique</h3>
                <p class="margin-top-20px">Nous avons converti nos parcelles en Bio en 2015. Ce choix, c'est celui d'une notion de respect, de liberté et de cohérence.
                <br><br>
                La conversion Bio est une première étapes pour nous. La suite? Inventer une agriculture de conservation. C'est à dire? Imaginer une forêts au beau milieu d'un champs composé que 10 cultures différentes. Des haies, des ruches, des bancs pour contempler la nature qui pousse,...
                <br><br>
                Une croyance : la nature porte en elle toutes les solutions.
                <br><br>
                Un vision : Challenger et penser le monde agricole.
                </p>
              </div>
            </div>
          </div>
        </div>


      </div>
    </section>


    <section class="wrapper-bg-white d-none">
      <div class="container">
        <h2 class="section-title-home" style="font-size:30px;">
          <div class="section-title-home-content" style="background-color: white;">
            Equipe
          </div>
        </h2>
        <div class="container">
          <div class="row">

            <div class="col-xs-12 col-sm-6 col-md-4">
              <div class="card-team" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('<%= image_path 'bertrand.png' %>');">
                <div class="card-category bg-green">Coach sportif</div>
                <div class="card-description">
                  <h2>Bertrand Matelart</h2>
                </div>
                <div class="card-user">
    <!--               <a href="#"><i class="fa fa-github"></i></a>
                  <a href="#"><i class="fa fa-instagram"></i></a>
                  <a href="#"><i class="fa fa-facebook"></i></a>
                  <a href="#"><i class="fa fa-twitter"></i></a> -->
                  <a href="#"><i class="fa fa-linkedin"></i></a>
                </div>
                <a class="card-link" href="#" ></a>
              </div>
            </div>
                    <div class="col-xs-12 col-sm-6 col-md-4">
              <div class="card-team" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('<%= image_path 'bertrand.png' %>');">
                <div class="card-category bg-green">Coach sportif</div>
                <div class="card-description">
                  <h2>Bertrand Matelart</h2>
                </div>
                <div class="card-user">
    <!--               <a href="#"><i class="fa fa-github"></i></a>
                  <a href="#"><i class="fa fa-instagram"></i></a>
                  <a href="#"><i class="fa fa-facebook"></i></a>
                  <a href="#"><i class="fa fa-twitter"></i></a> -->
                  <a href="#"><i class="fa fa-linkedin"></i></a>
                </div>
                <a class="card-link" href="#" ></a>
              </div>
            </div>
                    <div class="col-xs-12 col-sm-6 col-md-4">
              <div class="card-team" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('<%= image_path 'bertrand.png' %>');">
                <div class="card-category bg-green">Coach sportif</div>
                <div class="card-description">
                  <h2>Bertrand Matelart</h2>
                </div>
                <div class="card-user">
    <!--               <a href="#"><i class="fa fa-github"></i></a>
                  <a href="#"><i class="fa fa-instagram"></i></a>
                  <a href="#"><i class="fa fa-facebook"></i></a>
                  <a href="#"><i class="fa fa-twitter"></i></a> -->
                  <a href="#"><i class="fa fa-linkedin"></i></a>
                </div>
                <a class="card-link" href="#" ></a>
              </div>
            </div>
                    <div class="col-xs-12 col-sm-6 col-md-4">
              <div class="card-team" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('<%= image_path 'bertrand.png' %>');">
                <div class="card-category bg-green">Coach sportif</div>
                <div class="card-description">
                  <h2>Bertrand Matelart</h2>
                </div>
                <div class="card-user">
    <!--               <a href="#"><i class="fa fa-github"></i></a>
                  <a href="#"><i class="fa fa-instagram"></i></a>
                  <a href="#"><i class="fa fa-facebook"></i></a>
                  <a href="#"><i class="fa fa-twitter"></i></a> -->
                  <a href="#"><i class="fa fa-linkedin"></i></a>
                </div>
                <a class="card-link" href="#" ></a>
              </div>
            </div>
                    <div class="col-xs-12 col-sm-6 col-md-4">
              <div class="card-team" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('<%= image_path 'bertrand.png' %>');">
                <div class="card-category bg-green">Coach sportif</div>
                <div class="card-description">
                  <h2>Bertrand Matelart</h2>
                </div>
                <div class="card-user">
    <!--               <a href="#"><i class="fa fa-github"></i></a>
                  <a href="#"><i class="fa fa-instagram"></i></a>
                  <a href="#"><i class="fa fa-facebook"></i></a>
                  <a href="#"><i class="fa fa-twitter"></i></a> -->
                  <a href="#"><i class="fa fa-linkedin"></i></a>
                </div>
                <a class="card-link" href="#" ></a>
              </div>
            </div>
                    <div class="col-xs-12 col-sm-6 col-md-4">
              <div class="card-team" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('<%= image_path 'bertrand.png' %>');">
                <div class="card-category bg-green">Coach sportif</div>
                <div class="card-description">
                  <h2>Bertrand Matelart</h2>
                </div>
                <div class="card-user">
    <!--               <a href="#"><i class="fa fa-github"></i></a>
                  <a href="#"><i class="fa fa-instagram"></i></a>
                  <a href="#"><i class="fa fa-facebook"></i></a>
                  <a href="#"><i class="fa fa-twitter"></i></a> -->
                  <a href="#"><i class="fa fa-linkedin"></i></a>
                </div>
                <a class="card-link" href="#" ></a>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
</style>
