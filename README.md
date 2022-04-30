# rylefuentes.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
   
    <link rel="stylesheet" href="front.css" media="screen">
    <style>
        html{
    scroll-behavior: smooth;
}



body{
    margin: 0;
    background: linear-gradient(hsla(0, 0%, 100%, 0.65), hsla(0, 0%, 50%, 0.6), hsla(0, 0%, 0%, 0.9) 80%),
                url(https://i.pinimg.com/originals/a2/35/f4/a235f4394ef39feb1058efd7d82bd939.jpg);
    background-size:cover;
    background-position: center left;
    background-repeat: no-repeat;
    max-height: max-content;
    
}

*{
    box-sizing: border-box;
}


.headercont{
    border:none;  
    width: auto;
}


header{
    width: 100%;
    padding: 30px;
    border-bottom: 2px solid rgb(0, 0, 0);
    background: linear-gradient( hsla(0, 0%, 100%, 0.6), hsla(0, 0%, 0%, 0.9) 80%) ;
}


.logo{
    border: 2px solid white;
    color: white;
    font-family: Broadway;
    font-size: 35px;
    max-width: max-content;
    float: left;
}

header nav *{
    text-decoration: none;
    color: white;
}
header nav{
    padding: 10px;
   text-align: right;
   word-spacing: 10px;
   
}

header li{
    font-family: broadway;
    list-style: none;
    display: inline;
    

}

#menu{
    font-size: 12px;
    padding: 5px;
}

#menu:hover{
    box-shadow: 0 0 3em rgb(107, 243, 188);
    background: purple;
    border-radius: 30px;
    color: black;
}

.container{
    padding: 2em;
    width: 100%;
}


.contain {
    max-height: max-content;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 1.5em;
    width: 100%;
    text-align: center;
    
}
#text{
    height: max-content;
    font-family: century gothic;
    color: rgb(0, 0, 0);
    font-size: 20px;
    background: rgba(255, 255, 255, 0.2);
    padding: 4px;
    border-radius: 8px;
    max-width: 300px;
    align-self: center;
}

.firstpic{
    background-image: url(https://www.desktophut.com/wp-content/uploads/2022/01/Apex-Legends-Ash-Hd-Live-Wallpaper/Apex-Legends-Ash-Hd-Live-Wallpaper_thumbnail.jpg);
    background-size:cover;
    background-position: center top;
    background-repeat: no-repeat;
    align-self: center;
    width: 100%;
    max-width: 500px;
    height: 350px;
    box-shadow: 0 0 2em blueviolet;
    border-radius: 15px;
}   

footer{
    padding: 30px;
    border: none;
    gap: 5em;
    text-align: center;
    list-style: none;
    background:linear-gradient(hsla(0, 0%, 50%, 0.3), hsla(0, 0%, 0%, 0.75) 25%) 
}

footer li{
    color: white;
    font-size: 10px;
    font-family: century gothic;
}

#fb *{
    color: white;
    text-decoration: none;
}

#fb :hover{
    color: aqua;
}

.line{
    border: 2px solid black;
    height: 2mm;
    background: linear-gradient(aqua, blueviolet);
}

.contain2nd{
    border-top: 2px solid black;
    margin-top: 5em;
    background:url(https://wallpaperaccess.com/full/1767715.jpg) ;
    text-align: center;
    padding: 2em;
}

.contain2nd h1{
    color: white;
    font-family: broadway;
    font-size: 50px;
}

.contain2{
    width: 100%;
    padding: 2em;
    gap: 2em;
    display: flex;
    flex-direction: column;
    justify-content: center;
   
}


.titleContain{
    border: 2px;
    align-self: center;
}

.contain2 div{
    border: 2px solid rgb(89, 5, 5);
    width: 100%;
    max-width: 250px;
    height: 200px;
    margin: 0 auto;
    border-radius: 100%;

    
}

.image1{
    background: url(https://cdn.shopify.com/s/files/1/0553/9748/2672/products/GUEST_12e704d0-7630-44d1-a864-c42d3ddd2ac3_800x.jpg?v=1645190886);
    background-size: cover;
    background-position: center top;
    transition: 1s;
    opacity: .6;
    
}

.image1:hover{
    transform: scale(1.2) ;
    background: linear-gradient(white);
    box-shadow: 0 0 2em rgb(244, 71, 244);
    opacity: 1;
    border-radius: 15px;
    z-index: 5;
}

.image2{
    background-image: url(https://www.pngitem.com/pimgs/m/536-5366070_image-lifeline-apex-transparent-hd-png-download.png);
    background-size: cover;
    background-position: center top;
    transition: 1s;
    opacity: .7;
    z-index: 3;
}

.image2:hover{
    transform: scale(1.2);
    opacity: 1;
    z-index: 4;
    box-shadow: 0 0 2em rgb(244, 71, 244);
    border-radius: 15px;
}

.image3{
    background-image: url(https://esportspedia-apex.s3.amazonaws.com/1/18/Gibraltar.png);
    background-size: cover;
    background-position: center top;
    transition: 1s;
    opacity: .7;
    
}

.image3:hover{
    transform: scale(1.2);
    opacity: 1;
    z-index: 5;
    box-shadow: 0 0 2em rgb(244, 71, 244);
    border-radius: 15px;

}

@media (min-width: 5px) and (max-width: 769px) {
    #text{
        font-size: 13px;
    }
}


@media screen and (min-width: 770px) {
    #menu{
        font-size: 20px;
    }


    .contain{
        flex-direction: row-reverse;
    }

    .contain2{
        flex-direction: row;
    }

    .contain2 div{
        max-width: 500px;
    }
}
    </style>
    
</head>
<body>
    <div class="headercont">
        <header class="header">
            <div class="logo">Logo</div>
            <nav class="menu">
                <li><a href="#home" id="menu">Logo</a></li>
                <li><a href="#contact" id="menu">Contact</a></li>
            </nav>
        </header>
        
    </div>

    <div class="container">
            <div class="contain">
                <div class="firstpic"></div>
                
                <div id="text">
                all about apex Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magni soluta quis labore excepturi sed voluptates quidem recusandae, iusto neque assumenda.
                </div>
                
            </div>
    </div>    

            <div class="contain2nd">
                <h1>TEST</h1>

                <div class="contain2">

                    <div class="image1"></div>
                    <div class="image2"></div>
                    <div class="image3"></div>
                </div>
            </div>

        
    
    <footer id="contact">
        <li> rylefuentes09@gmail.com</li>
        <li id="fb"><a href="https://www.facebook.com/ryle.fuentes.9" target="_blank">https://www.facebook.com/ryle.fuentes.9</a> </li>
        <li>0935 781 7558</li>
    </footer>
</body>
</html>
