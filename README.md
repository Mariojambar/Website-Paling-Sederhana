# Website-Paling-Sederhana
Code html
<!doctype html>

<html lang="en">

  <head>

    <!-- Required meta tags -->

    <meta charset="utf-8">

    <meta name="viewport" content="width=device-width, initial-scale=1">

      <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>

  <link rel="stylesheet" href="./css/style.css">

  

      <!--Script bootstrap-->

  <script src="./js/style.js"></script>

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

  

  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

  

  <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">

    <!-- Bootstrap CSS -->

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    

    <link rel="stylesheet" href="style.css" type="text/css" media="assets/css/style.css">

    

    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">

    

    <link rel="apple-touch-icon" sizes="57x57" href="../img/icons/apple-icon-57x57.png">

    

    <link rel="apple-touch-icon" sizes="60x60" href="../img/icons/apple-icon-60x60.png">

    

    <link rel="apple-touch-icon" sizes="72x72" href="../img/icons/apple-icon-72x72.png">

    

    <link rel="apple-touch-icon" sizes="76x76" href="../img/icons/apple-icon-76x76.png">

    

    <link rel="apple-touch-icon" sizes="114x114" href="../img/icons/apple-icon-114x114.png">

    

    <link rel="apple-touch-icon" sizes="120x120" href="../img/icons/apple-icon-120x120.png">

    

    <link rel="apple-touch-icon" sizes="144x144" href="../img/icons/apple-icon-144x144.png">

    

    <link rel="apple-touch-icon" sizes="152x152" href="../img/icons/apple-icon-152x152.png">

    

    <link rel="apple-touch-icon" sizes="180x180" href="../img/icons/apple-icon-180x180.png">

    

    <link rel="icon" type="image/png" sizes="192x192" href="../img/icons/android-icon-192x192.png">

    

    <link rel="icon" type="image/png" sizes="32x32" href="../img/icons/favicon-32x32.png">

    

    <link rel="icon" type="image/png" sizes="96x96" href="../img/icons/favicon-96x96.png">

    

    <link rel="icon" type="image/png" sizes="16x16" href="../img/icons/favicon-16x16.png">

    

    <link rel="manifest" href="../img/icons/manifest.json">

    

    <meta name="msapplication-TileColor" content="#ffffff">

    

    <meta name="msapplication-TileImage" content="../img/icons/ms-icon-144x144.png">

    

    <meta name="theme-color" content="#ffffff">

    

    <title>YMarioP</title>

  </head>

  <body class="bg-dark">

        <main class="m-auto pt-5 pb-1">

      <section class="container profile text-center text-white">

       

  <div class="image-container">

    <img id="myImg" src="../assets/img/mario02.png" width="300" height="300" class="cover parallax" data-paralax-depth="2" style="cursor: pointer; margin-top: -100px;" title="Klik aku!">

    

  </div>

  <hr>

       <h1 class="text-info">Yohanes Mario Pangestu</h1>

       <hr>

  <div class="bg parallax" style="background-position-y: -11.1667px;">

    <div class="textbox">

      <h2 class="htbox">Siapa Mario?</h2>

      <p>Hai! Nama saya Yohanes Mario Pangestu.

        lahir pada 05 oktober 2009 di-Kota Bekasi dan

        saya adalah anak yang hidup dikeluarga sederhana,Mempunyai Kakak yang sudah bekerja.

        Saya adalah anak yang hidup di jaman Modern ini,Senang membaca manga melalui Hp,Dan terkadang Saya suka menonton Anime,hobi saya adalah bermain basket.

        belajar berbagai macam hal mulai dari editing video,programming,dan hal-hal yang berhubungan dengan komputer,yang menurut saya menarik.

        </p>

     <p>Memiliki keahlian dalam bidang-

       <br> <b>Web Development</b> (HTML,CSS dan Python)

      </p>

    </div>

  </div>

    <!-- The Modal -->

  <div id="myModal" class="modal">

    <span class="close">×</span>

    <img class="modal-content" id="img01">

    <div id="caption"></div>

  </div>

  <script>

    // Get the modal

    var modal = document.getElementById("myModal");

    // Get the image and insert it inside the modal - use its "alt" text as a caption

    var img = document.getElementById("myImg");

    var modalImg = document.getElementById("img01");

    var captionText = document.getElementById("caption");

    img.onclick = function () {

      modal.style.display = "block";

      modalImg.src = this.src;

      captionText.innerHTML = this.alt;

    }

    // Get the <span> element that closes the modal

    var span = document.getElementsByClassName("close")[0];

    // When the user clicks on <span> (x), close the modal

    span.onclick = function () {

      modal.style.display = "none";

    }

  </script>

       <footer id="footer">

  <hr>

  <div class="container">

    <!-- Row -->

    <div class="row">

      <div class="col-md-12">

        <!-- footer follow -->

        <ul class="footer-follow">

          <li><a href="https://ymariop.wordpress.com/"><i class="fa fa-envelope"></i></a></li>

          <li><a href="https://github.com/Mariojambar"><i class="fa fa-github" title="Kepoin Keseharian Kita!"></i></a></li>

           <li><a href="https://www.youtube.com/channel/UCefVd3UurOIY7hlcZO-NoWA"><i class="fa fa-youtube"></i></a></li>

        </ul>

        <!-- /footer follow -->

        <!-- footer copyright -->

        <div class="footer-copyright">

          <p class="text-white"><b>Copyright © 2022.</b> <br><b><span>-Designed by YMarioP</span></b>

          <hr>

          </p>

        </div>

        <!-- /footer copyright -->

      </div>

    </div>

    <!-- /Row -->

  </div>

  <!-- /Container -->

</footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

  </body>

</html>
