<!DOCTYPE html>
<html lang="fr">
	<head>
  <meta charset="utf-8">
  <title>Blog de Sacha et Pierre</title>

		 <link rel="alternate" href="http://php.net/manual/en/function.header.php" hreflang="en">
 <link rel="alternate" href="http://php.net/manual/pt_BR/function.header.php" hreflang="pt_BR">
 <link rel="alternate" href="http://php.net/manual/zh/function.header.php" hreflang="zh">
 <link rel="alternate" href="http://php.net/manual/fr/function.header.php" hreflang="fr">
 <link rel="alternate" href="http://php.net/manual/de/function.header.php" hreflang="de">
 <link rel="alternate" href="http://php.net/manual/ja/function.header.php" hreflang="ja">
 <link rel="alternate" href="http://php.net/manual/ro/function.header.php" hreflang="ro">
 <link rel="alternate" href="http://php.net/manual/ru/function.header.php" hreflang="ru">
 <link rel="alternate" href="http://php.net/manual/es/function.header.php" hreflang="es">
 <link rel="alternate" href="http://php.net/manual/tr/function.header.php" hreflang="tr">

<div class="header-category"><div id="nav" class="nav"><ul id="menu-menu-header-2" class="menu"><li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-29517"><a href="https://www.blogdesachaetpierre/notre-histoire/">Notre histoire</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-20996"><a href="https://www.blogdesachaetpierre/les-coins-tendances/">Les coins tendances</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-29518"><a href="https://www.blogdesachaetpierre/lechange-utilisateurs/">L'échange utilisateurs</a></li><li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-29516"><a href="https://www.blogdesachaetpierre/nous-contacter/">Nous contacter</a></li><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-32533"><a href="https://www.blogdesachaetpierre/rejoindre-laventure/">Rejoindre l'aventure</a></li></ul></div></div>
	<ul>Dans ce blog, vous allez découvrir les coins tendances du moment sur la Côte d'Azur, préparez-vous à en voir de toutes les couleurs ... :) </ul>
	<style>
       #map {
        height: 300px;
        width: 100%;
       }
    </style>
	</head>
<body>
<h1 style="color: midnightblue; font-size: 75px; text-align: center;">Blog de Sacha et Pierre</h1>
<div>
<a href="http://www.aufutetamesure.fr">
  <img src="./SachaetPierre.png" width="550" height="350" alt="Notre dernière expérience buvette, Le Füt et à mesure à Nice, France!!!" align="middle">
  </a>
  </div>
  &nbsp;
  <div style="text-align: justify;">
  Bonjour à tous, ce blog s'est créé autour d'une rencontre entre Pierre et moi. Après nos études à l'école de commerce EDHEC de Nice, tous deux passionnés d'aventures et de découvertes, nous avons décidé de créer un blog regroupant nos expériences passées, mais surtout de permettre à d'autres personnes de pouvoir explorer le monde. Et oui, nous vous permettrons de découvrir la côte d'azur dans tous ces coins plein de magies et de finesses, autour de buvettes, de restaurants typiques, mais aussi de danses et de sports. Ce blog est donc une ouverture et une invitation à toutes les personnes qui aimeraient découvrir le sud de la france en magie! Si cette aventure avec vous se montre positive, nous vous ferons explorer d'autres territoires bien plus que merveilleux, à l'aide d'une carte interactive qui vous notifiera les coins tendances du moment situés au plus près de chez vous ou de votre position à l'aide de pop-ups. Nous adorons poster des articles, mais surtout de faire partager des rencontres, des paysages, des coins tendances, des économies sur des vêtements, et bien plus encore! Notre blog sera un lien de visualiser les expériences de chacun mais aussi un moyen de communiquer avec d'autres utilisateurs, à l'aide d'un chatbot et d'un forum qui sera disponible très bientôt afin de permettre à chacun de pouvoir discuter et d'échanger, car le bonheur est avant tout dans le partage! En espérant que ces moments vous en seront agréables et nous restons disponibles si jamais vous souhaitez nous contacter...
	  <h2>Notre carte interactive</h2>
    <div id="map"></div>
    <script>
      function initMap() {
        var uluru = {lat: 43.69673299999999, lng: 7.271848999999975};
        var map = new google.maps.Map(document.getElementById('map'), {
          zoom: 15,
          center: uluru
        });
        var marker = new google.maps.Marker({
          position: uluru,
          map: map
        });
      }
    </script>
    <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDZOw3OHHYZUbXzfVgLlCEXdM4orajaAnc&callback=initMap">
    </script>
</div>
</body>
</html>
