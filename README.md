[index.html](https://github.com/user-attachments/files/23694970/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="cont">
     <nav class="navbar navbar-expand-lg px-3">
    <a class="navbar-brand " class="logo" href="#">Burger</a>
    
    <!-- زر الهمبرغر -->
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
    </button>

    <!-- القائمة -->
    <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
            <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
            <li class="nav-item"><a class="nav-link" href="#">About</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Menu</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Delevery</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
    </div>
</nav>
  </div>
  
     <div class="container">
      <div class="count">
   <div class="text">
        <h1>Love Every Burger</h1>
        <p>We serve the best burger on the piant.
          paving the way for cooking and preparing hot
          delicious burgers
        </p>
        <button>Teste Now</button>
    </div> 
        <div class="imgg">
          <img src="photo/home.png" alt=""></div>
          
      </div>
      </div>
  
  </div>
  

    <section class="about">
       <h1>About Us</h1>
       <div class="cont">
             <div class="im">
              <!-- <img  class="poteto" src="photo/poteto.png" alt="">
              <img  class="potet" src="photo/poteto.png" alt="">
              <img class="le" src="photo/le.png" alt=""> -->
               <img src="photo/photo_2025-11-17_20-17-58-removebg-preview.png" alt="">
      </div>
      <div class="text">
         <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.
           Tempore, est necessitatibus! Repellat magni, nulla amet modi 
           dolorum doloribus, rem distinctio ex reprehenderit voluptas,
           </p>
            <p>Lorem ipsum dolor sit amet consectetro quibusdam voluptates numquam doloribus expedita vel praesentium accusantium? Libero, quod quisquam.</p>
        
      </div>
       </div>
    </section>
   
      <section class="menu">
    <h1>Our Menu</h1>
      <div class="card">
        <div class="item">
          <img src="photo/burger2.png">
          <p>Chicken <br> Burger</p>
          <h4>6$</h4>
        </div>
        <div class="item">
          <div class="immg">
              <img src="photo/burger3.png" alt="">
          </div>
          
          <p>Meat <br>Burger</p>
          <h4>12$</h4>
        </div>
        <div class="item">
          <img class="big" src="photo/burger2.png" alt="">
          <p>big <br> Burger</p>
          <h4>10$</h4>
          
        </div>
        <div class="item">
          <img src="photo/burger4.png" alt="">
          <p>Grill<br> Burger</p>
          <h4>15$</h4>
        </div>
        <div class="item">
          <img src="photo/burger3.png" alt="">
          <p>Clasic <br>Burger</p>
          <h4>6$</h4>
        </div>
      </div>
   </section>  
   
          <section class="delivery">
          <div class="name">
               <h1>Fast Delivery</h1>
          </div>
          
          <div class="count">
                  <div class="text">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga quam harum cupiditate et incidunt excepturi, odit voluptates iure sit quo possimus nemo laborum dicta beatae, 
            maiores minus reiciendis, praesentium repellendus.</p>
            <button >contact Now</button>
          </div>
           <div class="immgg">
            <img src="photo/burger4.png" alt="">
           </div>
          </div>
          </section> 
             <section class="contact">

                <h1>Contact Now</h1>
                <div class="containerr">
                        <div class="delv2">
                   <img src="photo/delivery.png" alt="">
              </div>
              <div class="delv2">
                  <h3>Write Us</h3>

                  <h3>Find us here</h3>
                  <p>syria-swaida</p>

              </div>
              <div class="delv2">
                  <h3>Call Now and Order</h3>
                  <p>+9639777777</p>
                  <p>+110918329</p>
              </div>
              
                   
                </div>
            </section>    

 <footer>@All rights reseved | Made by Douaa Alsehnawi</footer>










    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
     <script>
        const hamburger = document.getElementById("hamburger");
        const navLinks = document.getElementById("navLinks");

        hamburger.addEventListener("click", () => {
            hamburger.classList.toggle("active");
            navLinks.classList.toggle("active");
});
     </script>
    <!-- <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">burger</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Recipe</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Poupuler</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">Delevery</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav> -->



    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
</body>
</html>
