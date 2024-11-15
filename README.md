![img1](https://github.com/user-attachments/assets/54ef2616-5011-49be-bb3b-859e25bce449)
![img2](https://github.com/user-attachments/assets/7e5fd714-7d3c-447a-b5f8-bf2f54d60845)
![img3](https://github.com/user-attachments/assets/1b79374b-4dbe-4eef-9434-2f3f91a1f5c9)
![img4](https://github.com/user-attachments/assets/fd4a6c72-5860-425a-8000-d03ba6658c28)
![img5](https://github.com/user-attachments/assets/1170f060-0263-4b52-902e-007dda2a6e8f)
![img6](https://github.com/user-attachments/assets/87ebc1fc-9b20-46ad-8bd1-027ea32e9d3d)

![img8](https://github.com/user-attachments/assets/568e3d43-3511-4e94-8b12-bf7a12f646cf)
![img9](https://github.com/user-attachments/assets/c6d6fc1f-fcc2-427c-b2e9-70f937f648d5)
webpage.html: 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Trendy and stylish clothing brand for all occasions">
    <title>Your Clothing Brand</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

/* Navbar Styling */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    padding: 1rem 2rem;
}

.navbar .logo a {
    color: #fff;
    font-size: 2rem;
    text-decoration: none;
}

.navbar .nav-links {
    list-style: none;
    display: flex;
}

.navbar .nav-links li {
    margin-left: 20px;
}

.navbar .nav-links a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
}

/* Hero Section */
.hero-section {
    background: url('https://via.placeholder.com/1600x800') no-repeat center center/cover;
    height: 60vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    padding: 0 20px;
}

.hero-section h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero-section p {
    font-size: 1.25rem;
    margin-bottom: 1.5rem;
}

.hero-section .cta-button {
    padding: 12px 25px;
    background-color: #ff6347;
    color: white;
    font-size: 1.1rem;
    text-decoration: none;
    border-radius: 5px;
}

/* Product Showcase */
.product-showcase {
    padding: 4rem 2rem;
    text-align: center;
}

.product-showcase h2 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
}

.products {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}

.product {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    width: 300px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.product img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.product h3 {
    font-size: 1.5rem;
    margin: 15px 0;
}

.product p {
    font-size: 1.25rem;
    color: #333;
}

.product .btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #333;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.product .btn:hover {
    background-color: #ff6347;
}

/* About Section */
.about-section {
    background-color: #fff;
    padding: 3rem 2rem;
    text-align: center;
}

.about-section h2 {
    font-size: 2rem;
    margin-bottom: 1.5rem;
}

/* Footer Section */
.footer {
    background-color: #333;
    color: white;
    padding: 1.5rem 2rem;
    text-align: center;
}

.footer .social-links {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

.footer .social-links li a {
    color: white;
    text-decoration: none;
}

.footer .social-links li a:hover {
    color: #ff6347;
}
    </style>
</head>
<body>

    <!-- Navbar -->
    <header>
        <nav class="navbar">
            <div class="logo">
                <a href="#">ROCK</a>
            </div>
            <ul class="nav-links">
                <li><a href="">Home</a></li>
                <li><a href="womens.html">Womens</a></li>
                <li><a href="mens.html">Mens</a></li>
                <li><a href="child.html">Children</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="hero-section">
        <div class="hero-content">
            <h1>Stay Stylish, Stay Comfortable</h1>
            <p>Explore the latest trends in fashion with our premium collection.</p>
            <a href="#shop" class="cta-button">Shop Now</a>
        </div>
    </section>

    <!-- Product Showcase -->
    <section id="shop" class="product-showcase">
        <h2>Our Collection</h2>
        <div class="products">
            <div class="product">
                <img src="data:image/jpeg;base64,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" alt="Product 1">
                <h3>Modern Jacket</h3>
                <p>$120.00</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product">
                
                <img src="data:image/jpeg;base64,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" alt="Product 2">
                <h3>Casual T-Shirt</h3>
                <p>$40.00</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product">
                <img src="data:image/jpeg;base64,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" alt="Product 3">
                <h3>Leather Shoes</h3>
                <p>$90.00</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about-section">
        <h2>About Us</h2>
        <p>We are a clothing brand focused on quality, comfort, and style. Our collections are designed to cater to modern-day fashion enthusiasts who value both aesthetics and functionality. We believe fashion should empower individuals and boost confidence.</p>
    </section>

    <!-- Footer Section -->
    <footer id="contact" class="footer">
        <div class="footer-content">
            <p>&copy; 2024 Your Clothing Brand. </p>
            <ul class="social-links">
                <li><a href="https://www.facebook.com/">Facebook</a></li>
                <li><a href="https://www.instagram.com/">Instagram</a></li>
                <li><a href="https://x.com/">Twitter</a></li>
            </ul>
        </div>
    </footer>

</body>
</html>

womens.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        div{
            border: 5px outset ;
        }
        .div1{
            height: 400px;
            width: 400px;
            margin-top: 30px;
            
            margin-left: 80px;
        }
        .div2{
            height: 400px;
            width: 400px;
            margin-top: 30px;
            margin-left: 40px;
            
        }
        .div3{
            height: 400px;
            width: 400px;
            margin-top: 30px;
            
            margin-left: 40px;
        }
        .div4{
            margin-top: 20px;
            margin-left: 500px;
        }
        h1{
            text-align: center;
            font-size: 40px;
        }
    </style>
</head>
<body>
    <div>
    <img src="https://manyavar.scene7.com/is/image/manyavar/MOHEY_WOMEN%20LANDING%20PAGE_Desktop_2500x1042-01_17-09-2024-07-09?$WT_HP%2FMLP%2FWLP_Hero_D$" alt=""><br>
    <img  class="div4" src="https://manyavar.scene7.com/is/content/manyavar/website---sfcc/vector-animation/bride_compressed_12-04-2023-08-02.gif" alt=""><br>
    <h1>Curate A Look For The
        Bridal Journey</h1>
    <img class="div1" src="https://manyavar.scene7.com/is/image/manyavar/WLP_Explore_Indo_D_21-09-2023-05-27?$WT%5FWLP%2FCategory2%5FD$" alt="">
    <img class="div2" src="https://manyavar.scene7.com/is/image/manyavar/WLP_Explore_Sarees_D_21-09-2023-05-29?$WT%5FWLP%2FCategory2%5FD$" alt="">
    <img class="div3" src="https://manyavar.scene7.com/is/image/manyavar/WLP_ShopInsta_T3_D_16-01-2023-10-04?$WT_MLP%2FWLP_ShopInsta%20_D$" alt="">
    </div>
</body>
</html>

mens.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            border:  5px solid;
            height: 700px;
            
            
        }
        .div1{
            margin-top: 50px;
            margin-left: 180px;
        }
        .div2{
            
        }
        .div3{
            border: 2px solid black;
            height: 50px;
            width: 250px;
            float: left;
            margin: 20px;
            text-align: center;
        }
        .h1{
            font-size: 50px;
            
        }
    </style>
</head>
<body>
    <div class="div1">
        <h1 class="h1">NEW ARRIVAL</h1>
    <img src="https://manyavar.scene7.com/is/image/manyavar/SHOS309_319-Peach.3336_21-02-2024-13-13:283x395" alt="">&nbsp;
    <img src="https://manyavar.scene7.com/is/image/manyavar/8905100831528.6019_30-03-2023-01-40:283x395" alt="">&nbsp;
    <img src="https://manyavar.scene7.com/is/image/manyavar/JAST160D_319-Peach.8789_03-12-2023-19-25:283x395" alt="">&nbsp;
    <img src="https://manyavar.scene7.com/is/image/manyavar/LJST009_326-FEROZE.5220_14-10-2023-16-49:283x395" alt="">&nbsp;
    <div class="div2">
        <div class="div3">
            Peach Buta Patterned Sherwani Set <br>$100</div>
        <div class="div3">Rosewater Pink Diamond Patterned Indo Western Set <br>$150</div>
        <div class="div3">Coral Pink Floral Patterned Kurta Jacket Set <br>$100</div>
        <div class="div3">Teal Blue Luxe Kurta Jacket Set <br>$120</div>

    </div>
    </div>
</body>
</html>

child.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .div1{
            border: 2px solid;
            margin-left: 20px;
            height: 1400px;
            
        }
        
        
        
            
        .div3{
            margin-left: 100px;
            margin-top: 30px;
        }
        .div4{
            border: 2px solid;
            width: 250px;
            height: 40px;
            margin-left: 150px;
            text-align: center;
        }
        .div5{
            border: 2px solid;
            width: 250px;
            height: 40px;
            text-align: center;
            margin-left: 460px;
        }
        .div6{
            border: 2px solid;
            width: 250px;
            height: 40px;
            text-align: center;
            margin-left: 530px;
        }
        .div7{
            border: 2px solid;
            width: 250px;
            height: 40px;
            text-align: center;
            margin-left: 70px;
        }
        .div8{
            border: 2px solid;
            width: 250px;
            height: 40px;
            text-align: center;
            margin-left: 500px;
        }
        .div9{
            border: 2px solid;
            width: 250px;
            height: 40px;
            text-align: center;
            margin-left: 480px;
            
        }
        .div11{
            margin-top: 120px;
            margin-left: 50px;
            margin: 50px;
        }
        .div12{
            margin: 40px;
            margin-top: 160px;
        }
        .div13{
            margin: 30px;
        }

        
        
    </style>
</head>
<body>
    <div class="div1">
    <img class="div3" src="https://images.bestsellerclothing.in/data/only-kids/14-mar-2023/155222002_g0.jpg?width=380&height=500&mode=fill&fill=blur&format=auto" alt="">
    <img class="div3" src="https://images.bestsellerclothing.in/data/only-kids/june-24-2022/227362201_g1.jpg?width=380&height=500&mode=fill&fill=blur&format=auto" alt="">
    <img class="div3" src="https://images.bestsellerclothing.in/data/only-kids/2-nov-2022/299440301_g0.jpg?width=380&height=500&mode=fill&fill=blur&format=auto" alt=""><br><br>
    <div class="div2">
        <div class="div4">child wear: $150
            
        <div class="div5">Shirt: $100
        <div class="div6">set: $150</div></div></div>    </div><br>
    <img class="div11" src="https://images.bestsellerclothing.in/data/only-kids/2-nov-2022/153735802_g0.jpg?width=380&height=500&mode=fill&fill=blur&format=auto" alt="">
    <img class="div12" src="https://images.bestsellerclothing.in/data/only-kids/2-nov-2022/153735803_g0.jpg?width=380&height=500&mode=fill&fill=blur&format=auto" alt="">
    <img class="div13" src="https://images.bestsellerclothing.in/data/only-kids/19-sep-2022/299436501_g0.jpg?width=380&height=500&mode=fill&fill=blur&format=auto" alt="">
            <div class="div10">
            <div class="div7">$300
            <div class="div8">$250
            <div class="div9">$150</div></div></div></div>
    </div>
</body>
</html>

National.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color: aqua;
            text-align: center;
            margin-top: 50px;
        }
    </style>
</head>
<body>
    <h1>Contact</h1>
    <label for="name"> Name: </label>
    <input type="Name" id="name"><br><br>
    <label for="num">Phone:</label>
    <input type="number" id="num"><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email"><br><br>
    <input type="submit" >
</body>
</html>

