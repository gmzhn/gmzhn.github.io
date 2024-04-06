# gmzhngl.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,
    initial-scale=1.0">
    <title>MEINE NEUE WEBSEIT</title>
    #<link rel="stylesheet" href="style.css">
    <style>@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap');

:root{
    --color_main:rgba(221, 134, 20, 0.66)
}
*{
    margin: 0;
    padding: 0;
}

.container{
    background: url('imgres?imgurl=https:%2F%2Fwww.uskudar.bel.tr%2Fuserfiles%2Fimages%2F5.png');
    height: 100vh;
    background-size: 100% 100%;
}

.container .navbar{
    width: 100%;
    height: 80px;
    background: var(--color_main);
}

.navbar .logo{
    display: inline-block;
    margin-left: 50px;
    margin-top: 20px;
}
.navbar .logo a{
    text-decoration: none;
    font-size: 30px;
    font-family: sans-serif;
    color:beige;

}


.navbar ul{
    float:right;
    margin-right: 20px;


}

.navbar ul li{
    list-style: none;
    display: inline-table;
    margin: 0 8px;
    line-height: 80px;

}

.navbar ul li a{
    color: white;
    text-decoration: none;
    font-size: 20px;
    padding: 6px 13px;
    font-family: Roboto;

}

.navbar ul li a.active,
.navbar ul li a:hover{
    background: #6d39a3;
    border-radius: 2px;
    transition: 5s;

}

.container.center{
    position:absolute ;
    top:50%;
    left:50%;
    transform: translate(-50%-50%);
    font-family: sans-serif;
    user-select: none;
}
.center h1{
    color: black;
    font-size: 70px;
    font-weight:bold;
    width: 900px;
    text-align: center;
}
.center h2{
    color: #fff;
    font-size: 50px;
    font-weight: bold;
    width:885px;
    margin-top:10px ;
    margin-left: 80px;

}
.center .buttons{
    margin:25px 270px;

}

.buttons button{
    height: 40px;
    width: 180px;
    font-size:20px;
    font-weight:bold ;

    color:#ffb3b3;
    background: var(--color_main);
    border:solid 1px red;
    cursor:pointer;
    outline: none;
    border-radius: 25px;
    transition: 5s;
}

.buttons button:hover{
    background: #fff;
}</style>
</head>
<body>
    <div class="container">
        <div class="navbar">
            <div class="logo">
                <a href="#">LOGO</a>
            </div>
            <ul>
                <li><a href="#" class="active">LERNPORTAL</a></li>
                <li><a href="#">LERNINHALTE</a></li>
                <li><a href="#">HOBBY</a></li>
                <li><a href="#">LOGIKSPIELE</a></li>
                <li><a href="#">ÜBER UNS</a></li>
            </ul>


            </div>
            <div class="center">
                <h1>HANGÜL'S WEBSITE</h1>
                <h2>WILLKOMMEN</h2>
                <div class="buttons">
                    <button>Mehr Information</button>
                    <button>Anfragen</button>
                </div>
        </div>
    </div>
</body>
</html>
