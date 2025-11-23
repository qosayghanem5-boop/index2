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
</nav> -->[style.css](https://github.com/user-attachments/files/23694974/style.css)
@import url('https://fonts.googleapis.com/css2?family=Aclonica&family=Josefin+Sans:ital,wght@0,100..700;1,100..700&family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Oswald:wght@200..700&family=Stack+Sans+Text:wght@200..700&display=swap');
*{
    padding: 0;[scrept.js](https://github.com/user-attachments/files/23694975/scrept.js)

    margin: 0;
    font-family: sans-serif;
}
body{
    background-color: rgba(251, 251, 199, 0.966);
      
}
:root{
}
  .nav{
  position: fixed;
  }
 .navbar{
 
    /* width: 100%;
    height: 100px; */
    /* background-color: #f4f136; */
    box-shadow: 0 4px 16px hsl(22, 100%, 8%,.2);
      
 }
 .navbar a{
     padding-left: 200px;
 }
.navbar-brand{
   
   font-size: 30px;
   font-weight: 600;
   margin-right: 300px;
}

.nav-item a{
    color: black;
    font-weight: 400; 
  
}
 .navbar ul li a{
    margin-right: 50px;
  }

.nav-item a::after{
    content: '';
    width: 0%;
    height: 2px;
    background: #f4f136;
    display: block;
    margin: auto;
    transition: .5s;
}
.nav-item a:hover::after{
    width: 100%;

}
.count{
    display: flex;
    align-items: center;
    justify-content: space-around;
    
   
}
.count .text{
    width: 300px;
      font-size: 20px;
}
.count .imgg img {
    padding-top: 150px;
    width: 400px;
 
}
.count h1{
    font-weight: 600;
  font-family: "Aclonica", sans-serif;
}
button{
    background-color: #ffc628;
    border-radius: 20px;
    padding: 8px 20px;
    border: none;
     transition: .5s;
}
button:hover{
    transform: scale(1.1);
}

  

@media (max-width:575px) {
      
.count .imgg img {
    display: none;
}   
.count .text {
    padding-top: 300px;
}
.count h1 {
    font-size: 60px;
}
p {
    margin-top: 30px;
    font-size: 20px;
}

}



/* ---------------------------------- */
.about .cont{
     width: 80%; 
   margin: auto;
   display: flex;
   justify-content: space-between;
   align-items: center;
}
.about .text{
    width: 600px;
    height: 800px;
    padding-top: 300px;
    margin-right: 300px;
    font-size: 20px;
}
.about h1{
    text-align: center;
    padding-top: 70px;
    
}
.about .poteto{
    width: 100px;
    position: absolute;
   right: 0;
   
   
}
.about .potet{
       width: 100px;
       rotate: 12deg;

}
.about .le{
      width: 90px;
}
/* .card{
    width: 80%;
    margin: auto;
    display: grid;
   grid-template-columns: repeat(3,2fr);
   gap: 1;
    
} */

@media (max-width:575px) {
    
img {
   
    width: 200px;
    padding-top: 200px;
}
p {
  
    width: 250px;
    height: 200px;
}






}
 /* ------------------------------------------------ */
 .card .item img{
    width: 150px;
   margin-top: -100px;
}
.menu h1{
    text-align: center;
}
.card{
  
     width: 80%;
    margin: auto;
    display: grid;
    grid-template-columns: repeat(3,2fr);
    gap: 20px;
    width: 600px;
    height: 500px;
    margin-bottom: 100px; 
      padding-top: 100px;
      background-color: rgba(251, 251, 199, 0.966); 
     border: none;
}
.item{
    border: 1px solid #000;
    border-radius: 10px;
    background-color: #ffc628;
    align-items: center;
    justify-content: center;
    padding: 40px;
}
.item p{
    font-weight: 600;
}
 .card.item.big img{
    width: 10px;
}
@media (max-width:575px) {
        
.menu.card .item {
    width: 10px;
    height: 10px;
     margin: 0;
     display: grid;
    grid-template-columns: repeat(2, 1fr);
}
.item{
       width: 200px;
    height: 600px;
    
}


}
/* -------------------- */
.delivery{
    padding-top: 100px;
     width: 80%;
    margin: auto;
    
 
}
.count .text{
    width: 400px;
    padding-bottom: 10px;
}

.delivery h1{
    text-align: center; 
    padding-top: 50px;
}
h3{
     font-family: "Aclonica", sans-serif;
}
.contact {
   
    width: 50%;
    margin-left: 450px;


}
.contact h1{
    
    text-align: center;
    padding-bottom: 50px;
}
.containerr{
    display: grid;
    grid-template-columns: repeat(3,1fr);
     background-color: #7f5539;
     padding-top: 100px;
   border-radius: 30px;

}
.containerr .delv2 img{
    width: 300px;
}
@media 
(max-width:575px) {
    button{
    margin-top: 90px;
    }
   .delivery {
   
 
    padding-top: 400px;

}
.delivery h1 {

    padding-top: 500px;
}
.containerr {
     display: block;
    width: 500px;
    padding-left: 200px;
    padding-top: 0;
    position: absolute;
    right: 0;
}
img {

    padding-top: 100px;
 
    padding-right: 100px;
    padding-bottom: 30px;


}


}
/* --------------------------------- */
footer{
    padding-top: 50px;
    padding-bottom: 30px;
    text-align: center;
}
@media (max-width:575px) {
    footer{
          margin-top: 1300px;
    }
     



}



    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
</body>
</html>
