# Ecommerce-Task-2
<!doctype html>
<html lang="en">
    <head>
        <title>Document</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@200&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="css/style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <style>
            *{
            margin:0;
            padding: 0;
            text-decoration: none;
            list-style: none;
            }
            body{
            font-family: 'Manrope', sans-serif;
            }
            header{
            background: url(https://fullhdpictures.org/wp-content/uploads/2019/08/Kylie-Jenner-Wallpaper.jpg)no-repeat center center/cover;
            width: 100%;
            height: 100vh;
            }

            .topnav {
            color: white;
            opacity: 0.9;
            overflow: hidden;
            background-color: #333;
            }
  
            .topnav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 17px;
            }

            .topnav a:hover {
            background-color: #ddd;
            color: black;
            }
            .topnav .icon {
            display: none;
            }
  
            @media screen and (max-width: 600px) {
            .topnav a:not(:first-child) {display: none;}
            .topnav a.icon {
            float: right;
            display: block;
            }
            }
  
            @media screen and (max-width: 600px) {
            .topnav.responsive {position: relative;}
            .topnav.responsive .icon {
            position: absolute;
            right: 0;
            top: 0;
            }
            .topnav.responsive a {
            float: none;
            display: block;
            text-align: left;
            }
            }

            .part-one{
            position: absolute;
            top: 30%;
            left: 40px;
            color: white;
            font-size: 26px;
            }
            .part-one button{
            padding: 10px 14px;
            background: white;
            color: black;
            border: none;
            border-radius: 3px;
            cursor: pointer;
            }
            .part-one button:hover{ 
            box-shadow: 0 0 4px white;
            }
            .part-two{
            width: 100%;
            margin: auto;
            }
            .part-two img{
            float: left;
            width: 400px;
            }
           .part-two button{
            margin: 20px;
            padding: 10px 14px;
            background: rgb(2, 2, 2);
            color: rgb(255, 255, 255);
            border: none;
            border-radius: 3px;
            cursor: pointer;
            }
            .one-info{
            padding: 30px;
            text-align: center;
            justify-content: center;
            font-size: 24px;
            }
            .part-tre{
            width: 100%;
            text-align: center;
            display: flex;
            padding-bottom: 30px;
            }
            .part-tre img{
            padding-top: 20px;
            width: 50%;
            }
            .for-info{
            cursor: pointer;
            width: 100%;
            display: flex;
            justify-content: space-around;
            text-align: center;
            padding-bottom: 30px;
            }
            .for-info img{
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
            max-width: 300px;
            margin: auto;
            width: 200px;
            border: 1px solid rgb(207, 207, 207);
            }
            .part-for h1{
            text-align: center;
            padding-top: 30px;
            }
            .for-info button{
            background:rgb(224, 81, 81);
            padding: 4px 9px;
            cursor: pointer;
            color: white;
            border: none;
            }
            .part-five{
            width: 100%;
            padding-top: 10px;
            display: flex;
            text-align: center;
            justify-content: center;
            align-items: center;
            font-weight: 60;
            color: white;
            background: url(https://images.wallpaperscraft.com/image/backpack_branch_forest_122562_1920x1080.jpg)no-repeat center center/cover;
            height: 40vh;
            }

            .part-six{
            width: 100%;
            padding-top: 40px;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding-bottom: 40px;
            display: flex;
            }

            .seven-info{
            background-color: #333;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: space-around;
            text-align: center;
            }
            .seven-info h2{
            color: white;
            }
            input{
            outline: none;
            font-size: 20px;
            border: none;
            }
            .seven-info .btn{
            color: white;
            cursor: pointer;
            padding: 4px 7px;
            background: rgb(224, 81, 81);;
            }
            .seven-info a{
            color: white;
            }
            .footer{
            width: 100%;
            }
            footer img{
            width: 100%;
            }
            .icons{
            display: flex;
            justify-content: center;
            text-align: center;
            }
            .icons .fa{
            background: #333;
            padding: 10px 14px;
            margin: 5px;
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
            color: white;
            }
            footer p{
            text-align: center;
            }
            @media (min-width: 320px) and (max-width: 500px){
            .part-two{
            text-align: center;
            }
            .part-tre{
            display: block;
            }
           .for-info{
            display: block;
            }
            .part-six{
            display: block;
            }
           .seven-info{
            display: block;
            flex-direction: column;
            }
            }
      </style>
    </head>
    <header>
        <div class="topnav" id="myTopnav">
            <a href="#home" class="active">Home</a>
            <a href="#news">News</a>
            <a href="#contact">Contact</a>
            <a href="#about">About</a>
            <a href="javascript:void(0);" class="icon" onclick="myFunction()">
              <i class="fa fa-bars"></i>
           </a>
       </div>
        <div class="part-one">
            <h1>Chic handbags <br>
            reimagined for modern life.</h1>
            <button>Shop now</button>
       </div>
   </header>
    <body>
        <div class="part-two">
            <img src="https://www.prada.com/content/dam/pradanux_products/1/1NE/1NE204/064F0638/1NE204_064_F0638_SLF.png" alt="">
            <div class="one-info">
                <h1>Designed for fashion. Crafted for sport.</h1>
                <p>We make products that effortlessly transition from day to night. From the board room to the fitness studio, and everywhere in between, each Nomads piece is thoughtfully created to be the perfect balance of form and function. </p>
                <button>Studio Bag</button>
           </div>
       </div>
       <div class="part-tre">
           <div class="tre-info">
                <img src="https://www.balenciaga.com/66/45/45353437gc_12_a_f.jpg" alt="">
                <h4>Luxury materials</h4>
                <p>
                    Constructed from luxury nylons, leathers, and custom hardware, 
                   featuring sport details such as hidden breathing vents, waterproof + antimicrobial linings,
                   and more.
                </p>
          </div>
           <div class="tre-info">
                <img src="https://unblast.com/wp-content/uploads/2018/08/Gravity-Shopping-Bag-Mockup-.jpg" alt="">
                <h4>Luxury materials</h4>
                <p>Constructed from luxury nylons, leathers, and custom hardware, featuring sport details such as hidden breathing vents, waterproof + antimicrobial linings, and more.</p>
           </div>
           <div class="tre-info">
                <img src="https://www.balenciaga.com/66/45/45353437gc_12_a_f.jpg" alt="">
                <h4>Luxury materials</h4>
                <p>Constructed from luxury nylons, leathers, and custom hardware, featuring sport details such as hidden breathing vents, waterproof + antimicrobial linings, and more.</p>
           </div>
       </div>
       <div class="part-for">
            <h1>FEATURED COLLECTION</h1>
            <div class="for-info">
                <div class="for-info-img">
                    <img src="https://cdn-images.farfetch-contents.com/12/21/78/47/12217847_22359993_480.jpg" alt="">
                    <h3>Studio Bag</h3>
                    <p>$450.00</p>
               </div>
               <div class="for-info-img">
                    <img src="https://cdn-images.farfetch-contents.com/12/21/78/47/12217847_22359993_480.jpg" alt="">
                    <h3>Studio Bag</h3>
                    <p>$450.00</p>
               </div>
               <div class="for-info-img">
                    <img src="https://cdn-images.farfetch-contents.com/12/21/78/47/12217847_22359993_480.jpg" alt="">
                    <h3>Studio Bag</h3>
                    <p>$450.00</p>
                    <button>SALE</button>
               </div>
               <div class="for-info-img">
                    <img src="https://cdn-images.farfetch-contents.com/12/21/78/47/12217847_22359993_480.jpg" alt="">
                    <h3>Studio Bag</h3>
                    <p>$450.00</p>
               </div>
           </div>
       </div>
    
        <div class="part-five">
            <h1>Why choose between fashion and function? Our bags combine high-quality fabrics and hardware with sport functionality.</h1>
       </div>
       <div class="part-six">
            <div>
                <i class="fa fa-check"></i>
                <p>We make products that effortlessly transition from day to night. From the board room to the fitness studio, and everywhere in between, each Nomads piece is thoughtfully created to be the perfect balance of form and function. </p>
                <h6>- The New York Times</h6>
            </div>
            <div>
                <i class="fa fa-check"></i>
                <p>We make products that effortlessly transition from day to night. From the board room to the fitness studio, and everywhere in between, each Nomads piece is thoughtfully created to be the perfect balance of form and function. </p>
                <h6>- The New York Times</h6>
           </div>
            <div>
                <i class="fa fa-check"></i>
                <p>We make products that effortlessly transition from day to night. From the board room to the fitness studio, and everywhere in between, each Nomads piece is thoughtfully created to be the perfect balance of form and function. </p>
                <h6>- The New York Times</h6>
           </div>
       </div>
       <div class="part-seven">
            <div class="seven-info">
                <a href="#">Search</a>
                <a href="#">Shipping and Return Policy</a>
                <a href="#">Tearm Of Services</a>
                <a href="#">Contact</a>
                <h2>NewsLetter</h2>
                <input type="email" placeholder="Email Address">
                <input class="btn" type="submit" value="Subscribe">
           </div>
       </div>
       <footer>
            <img src="https://cdn4.avada.io/media/shopify/2ffsezj.png" alt="">
            <div class="icons">
                <i class="fa fa-facebook"></i>
                <i class="fa fa-twitter"></i> 
                <i class="fa fa-pinterest"></i>
                <i class="fa fa-instagram"><a href="instagram/elis.metaliaj/"></a></i>
           </div>
            <p>© 2020 Powered By ELIS </p>
      </footer>
       <script>
            function myFunction() {
            var x = document.getElementById("myTopnav");
            if (x.className === "topnav") {
            x.className += " responsive";
            } else {
            x.className = "topnav";
            }
            }
       </script>
   </body>
</html>
