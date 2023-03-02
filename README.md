<!Doctype html>
<html lang="pt-br">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!--LINK DE REFERENCIA-->
    <link href="https://getbootstrap.com/docs/5.3/assets/css/docs.css" rel="stylesheet">
    <title>treinobootstrap</title>
    
  <!--css BOOSTRAP-->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  
    <!--NOSSO CSS-->
    <link rel="stylesheet"  href="style.css">
    <!--JS BOOTSTRAP-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js" integrity="sha384-oBqDVmMz9ATKxIep9tiCxS/Z9fNfEXiDAYTujMAeBAsjFuCZSmKbSSUnQlmh/jp3" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js" integrity="sha384-mQ93GR66B00ZXjt0YO5KlohRA5SY2XofN4zfuZxLkoj1gXtW8ANNCe9d5Y3eG5eD" crossorigin="anonymous"></script>
<!--Vamos inserir um Header, uma barra de navegação fixa e imagem da logo-->
<body style="background-color: rgb(106, 112, 112);">
    <header>   <!-- Navbar content -->
      <div>
      <nav class="navbar navbar-expand-lg" style="background-color: #ce1a98;">
        <img src="Logo nova sem fundo.png" width="200" height="250">
        <!-- Navbar content -->
      </nav>
    </div>
    </header>
    <!--meio da página-->
    <main> 
      <div id="carouselExample" class="carousel slide">
          <div class="carousel-inner">  
              <div class="carousel-item active"> <!--serve para o carrosel ficar visível-->
              <img src="capsula nh.webp" width="200" height="250">        
      </div>
      <div class="carousel-item">
        <img src="toniconh.jpg"  width="200" height="250" class="d-block w-100" alt="tonico"></div>
        <div class="carousel-item">
            <img src="kit nh.jpg"  width="200" height="250" class="d-block w-100" alt="kit completonh"></div>
            
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
</div>
</main><!--meio da página-->
   </body>
</html>
