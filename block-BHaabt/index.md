writeCode

- Create an insurance website according to the layout shown below.

![Web Typography Assignment level 2](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/web-typography/ex-2.png)

### Typography

**Heading**

Font Family: [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display?query=dm+se)

**Body**

Font Family: [Karla](https://fonts.google.com/specimen/Karla?query=karla)

- Using CSS resets is necessary.
- Use semantic tags and keep the nesting and indentation proper.
- Work on typography in detail.
<!---HTML-->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    
    <title>Document</title>
    <!--Font family-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=Karla:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,200;1,300;1,400;1,500;1,600;1,700;1,800&display=swap" rel="stylesheet">
    <!--Font Awesome-->
    <script src="https://kit.fontawesome.com/f98f63fd9d.js" crossorigin="anonymous"></script>

    <!--CSS--->
    <link rel="stylesheet" href="stylesheet/style.css">
  </head>
  <body>
    <header class="header ">
        <div class="container flex">
            <a class="brand" href="#">Prolnsure</a>
            <nav class="nav">
                <a href="#">HOME</a>
                <a href="#">ABOUT</a>
                <a href="#">CONTACT</a>
                <a class="btn" href="#">VIEW PLANS</a>
            </nav>
        </div>
    </header>
    <main>
        <section class="hero">
           <div class="container flex align ">
              <div class="col">
                <div class="line"></div>
                <h1>Humanizing your insurance</h1>
                <p class="text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis, nobis! Est, culpa voluptatibus inventore voluptates perspiciatis amet reprehenderit. .</p>
                <a class="btn" href="#">VIEW PLANS</a>
              </div>
              <div class="col padding">
                <img class="hero-img" src="assets/01.png" alt="fireworks">
              </div>

          </div>
        </section>
        <section class="about ">
            <article class="container flex">
                <div class="col">
                    <img class="-img" src="assets/02.png" alt="child with parent">
                </div>
                <div class="col">
                    <h2 class="heading ">About the insure</h2>
                    <p class="text about-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus, officia? Commodi quos voluptas exercitationem inventore molestias magnam, culpa .</p>
                    <a class="btn about-btn" href="#">Know More</a>
                </div>
                
            </article>
           
        </section>
        <section>
            <div class="container ">
              <header> 
                <div class="line"></div>   
                <h3 class="heading padding">We are different</h3>
              </header>
                <div class="flex">
                   <div class="col-left">
                     <i class="fas fa-user-cog"></i>
                     <h4 class="about-heading">Easy Process</h4> 
                     <p class="text feature-text">Lorem ipsum dolor sit amet consectetur
                        adipisicing elit. Eaque fugiat porro 
                        unde cumque? Culpa ab optio iste harum
                     </p>
                     </div>
                     <div class="col-left">
                       <i class="fas fa-user-cog"></i>
                       <h4 class="about-heading">Affordable Prices</h4> 
                       <p class="text feature-text">Lorem ipsum dolor sit amet consectetur
                          adipisicing elit. Eaque fugiat porro 
                          unde cumque? Culpa ab optio iste harum
                       </p>
                     </div>
                     <div class="col-left">
                       <i class="fas fa-user-cog"></i>
                       <h4 class="about-heading">You Come First</h4> 
                       <p class="text feature-text">Lorem ipsum dolor sit amet consectetur
                          adipisicing elit. Eaque fugiat porro 
                          unde cumque? Culpa ab optio iste harum
                       </p>
                     </div>
                </div>
            </div>
           
        </section>
        <section>
            <div class="cta-section padding">
              <div class="container flex  ">
                <h3>Find out more<br> about how we work</h3>
                <a class="btn " href="#"> HOW WE WORK</a>
              </div>
            </div>
        </section>
       
    </main>
    <footer class="footer">
        <div class="container ">
           <div class="flex">
             <a class="brand" href="#">Prolnsure</a>
             <nav class="nav social">
                <a href="#"><i class="fab fa-facebook-square"></i></a>
                <a href="#"><i class="fab fa-twitter-square"></i></a>
             </nav>
           </div>
           <hr>
           <nav class="nav">
              <a href="#" >Home</a>
              <a href="#" >About Us</a>
              <a href="#" >Contact Us</a>
              <a href="#" >How we work</a>
           </nav>
        </div> 
        <div class="copyright">
           <small> &copy AltCampus Services Pvt Ltd,2018-Present</small>
        </div>
    </footer>
  </body>
</html>