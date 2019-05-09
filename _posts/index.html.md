<!DOCTYPE html>
<html lang="fr">
  <head prefix="og: http://ogp.me/ns#">

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <!-- meta pour le référencement-->
    <meta name="description" content="Webagency est une agence web spécialisée dans les services d'UI Design, d'UX design et de SEO pour tous vos projets">
    <meta name="robots" content="noindex, nofollow">
    <title>Agence de projets Web</title>
    <!--- meta pour le referencement reseaux sociaux-->
    <meta property="og:title" content="L'agence de tous vos projets">
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Webagency">
    <meta property="og:url" content="http://maximelafitte.com">
    <meta property="og:image" content="http://maximelafitte.com/webagency/images/logo.png">


    <link rel="stylesheet" href="style.css"/>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.1.0/css/all.css" integrity="sha384-lKuwvrZot6UHsBSfcMvOkWwlCMgc0TaWr+30HWe3a4ltaBwTZhyTEggF5tJv8tbt" crossorigin="anonymous">
    <link rel="icon" type="image/x-icon" href="images/ico/favicon.ico"/>



  </head>

<body>


  <!-- HEADER -->
  <!-- HEADER -->
  <!-- HEADER -->

    <header id="header">

      <div class="logo">
        <img src="images/logo.png" alt="Logo de Webgency"/>
      </div>

      <nav>
        <ul>
          <li><a href="#">Accueil</a></li>
          <li><a href="#nos_services">Services</a></li>
          <li><a href="#nos_projets">Portfolio</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>


    </header>


  <!-- SECTION SLIDER -->
  <!-- SECTION SLIDER -->
  <!-- SECTION SLIDER -->



    <section id="container">

      <div class="fleche_gauche">
        <a href="#"><i class="fas fa-chevron-left fleche"></i></a>
      </div>

      <div class="fleche_droite">
        <a href="#"><i class="fas fa-chevron-right fleche"></i></a>
      </div>

      <div class="all_container slide">
        <img src="images/slider/bg1.jpg" alt="fille" class="picture_slider ps1"/>
        <img src="images/slider/bg2.jpg" alt="garcon" class="picture_slider ps2"/>
      </div>

      <div class="slide_pres">
        <h1><span>WEBAGENCY</span>: L'AGENCE DE TOUS VOS PROJETS !</h1>
        <p>Vous avez un projet web ? La WebAgency vous aide à le réaliser !</p>
        <div class="bouton_info">
          <a href="#nos_services">Plus d'infos</a>
        </div>
      </div>

      <span class="timeline"></span>

    </section>





  <!-- SECTION NOS SERVICES -->
  <!-- SECTION NOS SERVICES -->
  <!-- SECTION NOS SERVICES -->




    <section id="nos_services">

      <div class="titre_sections">
        <h2>NOS SERVICES</h2>
        <div class="separateur">
          <i class="fas fa-circle rond-bleu"></i>
          <hr>
        </div>
        <p>Confiez nous votre projet web et nous vous accompagnerons pour donner vie à des projets innovants et créatifs sur mesure.</p>
      </div>

      <div class="section_service">
        <div class="photo_service"><img src="images/main-feature.png" alt="Photo de nos services"></div>

        <div class="liste_services">

                <div class="UX">
                  <div class="icon_left">
                    <i class="fas fa-chart-line"></i>
                    <i class="fas fa-circle icone_service"></i>
                    </div>
                    <div class="UX_text">
                      <h3>UX design</h3>
                      <p>Notre savoir-faire technique nous permet de vous conseiller dans la conception fonctionnelle de votre projet. </p>
                  </div>
                </div>

                <div class="UI">
                  <div class="icon_left">
                    <i class="fas fa-cubes"></i>
                    <i class="fas fa-circle icone_service"></i>
                  </div>
                    <div class="UI_text">
                      <h3>UI design</h3>
                      <p>Nous sommes convaincus qu’un bon produit passe par un design adapté. C’est pourquoi designers et développeurs travaillent ensemble.</p>
                  </div>
                </div>

                <div class="SEO">
                  <div class="icon_left">
                    <i class="fas fa-chart-pie"></i>
                    <i class="fas fa-circle icone_service"></i>
                  </div>
                  <div class="SEO_text">
                      <h3>SEO</h3>
                      <p>Nous optimisons la visibilité de votre site auprès des internautes sur les recherches en rapport avec vos produits et services par le referencement naturel.</p>
                  </div>
          </div>

              </div>
      </div>
    </section>



  <!-- SECTION NOS PROJETS -->
  <!-- SECTION NOS PROJETS -->
  <!-- SECTION NOS PROJETS -->



    <section id="nos_projets">

      <div class="titre_sections">
        <h2>NOS PROJETS</h2>
        <div class="separateur">
          <i class="fas fa-circle rond-bleu"></i>
          <hr>
        </div>
        <p>Ils nous ont fait confiance. Voici quelques unes de nos réalisations.</p>
      </div>

      <div class="projects">

        <input id="select_type_all" name="radio_set_1" type="radio" class="select_all" checked/>
        <input id="select_type_1" name="radio_set_1" type="radio" class="select_1"/>
        <input id="select_type_2" name="radio_set_1" type="radio" class="select_2"/>
        <input id="select_type_3" name="radio_set_1" type="radio" class="select_3"/>

        <div class="label_nav">
          <label for="select_type_all" class="label_type_all">All Works</label>
            <i class="fas fa-caret-down" aria-hidden="true"></i>
          <label for="select_type_1" class="label_type_1">Créative</label>
            <i class="fas fa-caret-down" aria-hidden="true"></i>
          <label for="select_type_2" class="label_type_2">Corporate</label>
            <i class="fas fa-caret-down" aria-hidden="true"></i>
          <label for="select_type_3" class="label_type_3">Portfolio</label>
            <i class="fas fa-caret-down" aria-hidden="true"></i>
        </div>

        <ul class="projects_items">

          <li class="item_type_1">
            <figure>
              <img src="images/portfolio/01.jpg" alt="marque"/>
              <figcaption><span>Le Lunettier</span><br>Logo de la marque</figcaption>
              <i class="far fa-eye" aria-hidden="true"></i>
            </figure>
          </li>

          <li class="item_type_2">
            <figure>
              <img src="images/portfolio/02.jpg" alt="logo d'application web"/>
              <figcaption><span>Pink Rabbit</span><br>Application Web</figcaption>
              <i class="far fa-eye" aria-hidden="true"></i>
            </figure>
          </li>

          <li class="item_type_3">
            <figure>
              <img src="images/portfolio/03.jpg" alt="logo d'application web"/>
              <figcaption><span>Pompadour</span><br>Application Web</figcaption>
              <i class="far fa-eye" aria-hidden="true"></i>
            </figure>
          </li>

          <li class="item_type_1">
            <figure>
              <img src="images/portfolio/04.jpg" alt="site web"/>
              <figcaption><span>We are</span><br>Site</figcaption>
              <i class="far fa-eye" aria-hidden="true"></i>
            </figure>
          </li>

          <li class="item_type_2">
            <figure>
              <img src="images/portfolio/05.jpg" alt="site web"/>
              <figcaption><span>Mockup</span><br>Site de e-commerce</figcaption>
              <i class="far fa-eye" aria-hidden="true"></i>
            </figure>
          </li>

          <li class="item_type_3">
            <figure>
              <img src="images/portfolio/06.jpg" alt="site web"/>
              <figcaption><span>Skyline</span><br>Site d'agence touristique</figcaption>
              <i class="far fa-eye" aria-hidden="true"></i>
            </figure>
          </li>

          <li class="item_type_1">
            <figure>
              <img src="images/portfolio/07.jpg" alt="site d'un concours"/>
              <figcaption><span>Fusée</span><br>Jeu concours</figcaption>
              <i class="far fa-eye" aria-hidden="true"></i>
            </figure>
          </li>

          <li class="item_type_2">
            <figure>
              <img src="images/portfolio/08.jpg" alt="logo d'application"/>
              <figcaption><span>Paperwork</span><br>Application Web</figcaption>
              <i class="far fa-eye" aria-hidden="true"></i>
            </figure>
          </li>

        </ul>

      </div>

    </section>



  <!-- CONTACT -->
  <!-- CONTACT -->
  <!-- CONTACT -->



    <section id="contact">

      <div class="map">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2624.221609680716!2d2.347636915996972!3d48.87305177928899!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47e66e145ccb3091%3A0x9495beee8c96ec27!2s25+Rue+d&#39;Hauteville%2C+75010+Paris!5e0!3m2!1sfr!2sfr!4v1532357680083"></iframe>
      </div>

      <div class="overlay"></div>

      <div class="formulaire">
        <div class="adress">
          <h5>Contact Info</h5>
          <p><span>WebAgency SAS</span><br>25 rue d'Hauteville 75010 Paris<br><abbr title="Telephone">Tel :</abbr> 01 02 04 04 05</p>
        </div>

        <form action="/my_handling_form_page" method="post">
          <p><input type="text" name="user_name" placeholder="Name"/></p>
          <p><input type="text" name="user_mail" placeholder="Email"/></p>
                <p><input type="text" name="user_subject" placeholder="Subject"/></p>
              <p><textarea name="user_message" placeholder="Message"></textarea></p>
              <div class="bouton_info1">
            <a href="#">Send Message</a>
          </div>
          </form>
      </div>

    </section>




  <!-- FOOTER -->
  <!-- FOOTER -->
  <!-- FOOTER -->


  <footer>
    <div class="footer">Copyright de Maxime LAFITTE dans le cadre du projet Webagency d'openclassroom</div>
  </footer>


</body>
</html>
