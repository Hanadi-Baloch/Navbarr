# Navbarr
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="./images/image-removebg-preview.png" alt="" class="image">
            </div>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Gallery</a></li>
                <li><a href="#">Contact</a></li>
            </ul> 
            <div class="bnt"><a href="#">Shopping</a></div>
        </nav>
    </header>
</body>
</html>
*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;

}
body{
    width: 100vw;
    height: 100vh;
}
header{
    width: 100%;
    height: 70px;
    background-color: red;
    

}
nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.logo{
    /* background-color: yellow; */
    height: 70px;
    display:flex;
    justify-content: center;
    align-items: center;
   
}
.logo>img{
    width: 80px;
    height: 60px;
}
ul>li{
    color: white;
    display: inline;
    padding-left: 10px;
}
ul,li>a{
    text-decoration: none;
    color: white;
    font-size: 18px;
    font-weight: 700;
}
.bnt>a{
    text-decoration: none;
    color: black;
     background-color: yellow
     ;
     padding: 10px;
     border-radius: 10px;
}
#bar{
    line-height: px;
    width: 20px;
    height: 5px;
    color: black;
    background-color: black;
}
