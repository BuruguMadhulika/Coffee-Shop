# Coffee-Shop
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coffee | Shop</title>
    <link rel = "stylesheet" href = "stylecoffee.css">
</head>
<body>
    <div class="container">
        <div class="nav-bar">
            <h1 class = "title">Cof<span>fee</span></h1>
            <p>Coffee Shop</p>
            <ul class ="menu">
                <li><a href = "#">HOME</a></li>
                <li><a href = "#">PRODUCT</a></li>
                <li><a href = "#">SERVICES</a></li>
                <li><a href = "#">CONTACT</a></li>
                <li><a href = "#">ABOUT</a></li>
            </ul>
        </div>
        <div class="home">
            <h1 class="title-1">Good<span>Coffee</span>will always<br> Find the peace</h1>
            <p>we provide a variety of uniques and Best coffees</p>
            <button type = "button">Order Now</button>
        </div>
    </div>
</body>
</html>



*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.container{
    height: 100vh;
    width: 100%;
    background: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)),url(1076692.jpg);
    background-size: cover;
    background-position: center;
    font-family: Arial, Helvetica, sans-serif;
}
.nav-bar{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 30px 80px;
}
.nav-bar .title{
    color: #fff;
    font-size: 67px;
    font-weight: 600;
}
span{
    color: crimson;
}
.nav-bar p{
    position: absolute;
    margin-top: 100px;
    margin-left: 50px;
    color: #fff;
    font-size: 20px;
    font-weight: 500;
}
.menu li{
    list-style: none;
   display: inline-block;
}
.menu li a {
    text-decoration: none;
    color: #fff;
    font-size: 27px;
    font-weight: 600;
    margin-left: 25px;
    transition: .4s ease;
}
.menu li a:hover{
    color: crimson;
    padding: 10px 20px;
    border: 2px solid #fff;
}
.home{
    height: 400px;
    padding: 70px;
}
.title-1{
    font-size: 56px;
    color: #fff;
    font-weight: 600;
}
.home p{
    color: lemonchiffon;
    font-size: 20px; 
    padding-top: 10px;
}
.home button{
    height: 40px;
    color: #fff;
    background-color: crimson;
    font-size: 22px;
    padding: 5px 30px;
    margin-top: 20px;
    border: none;
    border-radius: 5px;
    transition: 4s ease;
    cursor: pointer;
    
}
.home button:hover{
    background: none;
    border: 2px solid crimson;
}

