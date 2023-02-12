# 1st-Project---Amogelang-Tsetse
HTML CSS Javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NEXT Website</title>
    <link rel="stylesheet" href="styles.css"/>

    <link
    rel="stylesheet"
    href="https://use.fontawesome.com/releases/v5.14.0/css/all.css"
    integrity="sha384-HzLeBuhoNPvSl5KYnjx0BT+WB0QEEqLprO+NBkkk5gbc67FTaL7XIGa2w1L0Xbgc"
    crossorigin="anonymous"
  />

  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Kumbh+Sans:wght@400;700&display=swap" rel="stylesheet">

    </head>
<body>
  <!--Navbar Section-->
  <nav class="navbar">
    <div class="navbar__container">
        <a href="/" id="navbar__logo">
          <i class="fas fa-gem"></i>NEXT</a>
        <div class="navbar__toggle" id="mobile-menu"> 
        <span class="bar"></span> 
        <span class="bar"></span> 
        <span class="bar"></span> 
        </div>
        <ul class="navbar__menu">
            <li class="navbar__item">
               <a href="/" class="navbar__links" id="Home">Home</a>
             </li>
             <li class="navbar__item">
               <a href="/tech.html" class="navbar__links" id="Tech">About</a>
             </li>
             <li class="navbar__item">
               <a href="/" class="navbar__links">Products</a>
             </li>
             <li class="navbar__btn">
               <a href="/" class="button">Sign Up</a>
             </li>
        </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="main">
    <div class="main__container">
      <div class="main__content">

    <h1>NEXT GENERATION</h1>
    <h2>TECHNOLOGY</h2>
    <p>See what makes up different!</p>

    <button class="main__btn"><a href="/">Get Started</a> </button>
    
      </div>
      <div class="main__img--container"> </div>
        <img src="pic1.svg" alt="pic1"id="main__img">     
    </div>
  </div>

  <script src="app.js"></script>
</body>
</html>
