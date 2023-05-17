﻿<!DOCTYPE html>

<html lang="en-US" xmlns="https://nagetsun.github.io/">
<head>
    <meta charset="utf-8" />
    <title>Name</title>
    <link rel="stylesheet" href="Main.css" />
</head>
<body class="Boby">
    <header class="Header">
        <div class="Item">
            <div class="Logo">
                <div><a href="" class="img_objkt"><img src="IkonM.jpg" class="img" /></a></div>
                <a href="" ><h1 class="Name">WaterAndFlame</h1></a>
            </div>
            <div class="Menu_opt">
                <ul class="Menu">
                    <li class="List">
                        <a href="" class="Button_Li1">Home</a>
                        <div class="triangle_bottom1"></div>
                        <div class="Bottom_menu1">
                            <ul class="spisok_bottom1">
                                <li>Post</li>
                                <li>Post</li>
                                <li>Post</li>
                            </ul>
                        </div>
                    </li>
                    <li class="List">
                        <a href="" class="Button_Li2">Home</a>
                        <div class="triangle_bottom2"></div>
                        <div class="Bottom_menu2">
                            <ul class="spisok_bottom2">
                                <li>Post</li>
                                <li>Post</li>
                                <li>Post</li>
                            </ul>
                        </div>
                    </li>
                    <li class="List">
                        <a href="" class="Button_Li3">Home</a>
                        <div class="triangle_bottom3"></div>
                        <div class="Bottom_menu3">
                            <ul class="spisok_bottom3"> 
                                <li>Post</li>
                                <li>Post</li>
                                <li>Post</li>
                            </ul>
                        </div>
                    </li>
                    <li class="List">
                        <a href="" class="Button_Li4">Home</a>
                        <div class="triangle_bottom4"></div>
                        <div class="Bottom_menu4">
                            <ul class="spisok_bottom4">
                                <li>Post</li>
                                <li>Post</li>
                                <li>Post</li>
                            </ul>
                        </div>
                    </li>
                </ul>
            </div>
            <div class="login">
                <a href="" class="Button_login">Log in</a>
                <a href="" class="Button_regust">Registration</a>

            </div>
        </div>
    </header>
</body>
</html>

li::marker {
    text-decoration: none;
}
a:link{
    text-decoration:none;
}
a:visited{
    text-decoration:none;
    color: none;
}
body{
    margin:auto;
}
h1{
    color: #393939;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.Boby {
    background-color: #fff;
}
.Header {
    background-color: #5CB2D7;
    height: 100px;
    width: 1440px;
    border-radius: 0px 0px 50px 50px;
}
.img {
    height: 70px;
    width: 70px;
    border-radius: 50%;
}
.img_objkt {
    display: flex;
    align-items: center;
    padding: 15px;
}
.Item {
    display: flex;
    flex-wrap: nowrap;
    align-items: center;
    justify-content: flex-start;
}
.Logo {
    display: flex;
    align-items: center;
}
.Name {
    color: #3059b7;
    transition: all 2s cubic-bezier(0.68, -0.55, 0.27, 1.55);
}
.Name:hover {
    color: #db1f1f
}
.Menu_opt {
    height: 100px;
    width: 850px;
}
.Menu {
    display: flex;
    align-items: flex-start;
    list-style-type: none;
    justify-content: space-evenly;
    flex-wrap: nowrap;
    margin-block: auto;
}
.List {
    height: 30px;
    width: 140px;
}
.Button_Li1 {
    height: 30px;
    width: 140px;
    background-color: #FF5722;
    border-radius: 0px 0px 25px 25px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #2b3940;
    transition: all 1s ease;
    z-index: 0;
    position: absolute;
}
.triangle_bottom1 {
    width: 0px;
    height: 0px;
    border-left: 6px solid transparent;
    border-right: 6px solid transparent;
    border-top: 11px solid #03A9F4;
    z-index: 1;
    top: 10px;
    position: absolute;
    margin-left: 115px;
    transition: all 1s ease;
    cursor: pointer;
    transform: scale(10s);
}
.Bottom_menu1 {
    background: #ffffff29;
    height: 80px;
    width: 140px;
    border-radius: 25%;
    margin-top: 45px;
    position: absolute;
    border: outset;
    opacity: 0;
    transition: 15s;
}
.spisok_bottom1 {
    list-style-type: none;
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    padding: 0px;
    align-items: center;
    width: 140px;
    height: 80px;
    justify-content: space-evenly;
    border-radius: 25%;
}
.triangle_bottom1:active + .Bottom_menu1 {
    transition:all 1s ease;
    opacity: 1;
}
.triangle_bottom1:active {
    width: 0px;
    height: 0px;
    border-left: 4px solid transparent;
    border-right: 4px solid transparent;
    border-top: 9px solid #03A9F4;
}
.Button_Li1:hover + .triangle_bottom1 {
    top: 15px;
}
.Button_Li1:hover {
    height: 40px;
}
.Button_Li2 {
    height: 30px;
    width: 140px;
    background-color: #FF5722;
    border-radius: 0px 0px 25px 25px;
    display: block;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #2b3940;
    transition: all 1s ease;
    position: absolute;
}
.triangle_bottom2 {
    width: 0px;
    height: 0px;
    border-left: 6px solid transparent;
    border-right: 6px solid transparent;
    border-top: 11px solid #03A9F4;
    z-index: 1;
    top: 10px;
    position: absolute;
    margin-left: 115px;
    transition: all 1s ease;
    cursor: pointer;
    transform: scale(10s);
}
.Bottom_menu2 {
    background: #ffffff29;
    height: 80px;
    width: 140px;
    border-radius: 25%;
    margin-top: 45px;
    position: absolute;
    border: outset;
    opacity: 0;
    transition: 15s;
}

.spisok_bottom2 {
    list-style-type: none;
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    padding: 0px;
    align-items: center;
    width: 140px;
    height: 80px;
    justify-content: space-evenly;
    border-radius: 25%;
}

.triangle_bottom2:active + .Bottom_menu2 {
    transition: all 1s ease;
    opacity: 1;
}
    .triangle_bottom2:active {
        width: 0px;
        height: 0px;
        border-left: 4px solid transparent;
        border-right: 4px solid transparent;
        border-top: 9px solid #03A9F4;
    }

.Button_Li2:hover + .triangle_bottom2 {
    top: 15px;
}
.Button_Li2:hover {
    height: 40px;
}
.Button_Li3 {
    height: 30px;
    width: 140px;
    background-color: #FF5722;
    border-radius: 0px 0px 25px 25px;
    display: block;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #2b3940;
    transition: all 1s ease;
    position: absolute;
}
.triangle_bottom3 {
    width: 0px;
    height: 0px;
    border-left: 6px solid transparent;
    border-right: 6px solid transparent;
    border-top: 11px solid #03A9F4;
    z-index: 1;
    top: 10px;
    position: absolute;
    margin-left: 115px;
    transition: all 1s ease;
    cursor: pointer;
    transform: scale(10s);
}
.Bottom_menu3 {
    background: #ffffff29;
    height: 80px;
    width: 140px;
    border-radius: 25%;
    margin-top: 45px;
    position: absolute;
    border: outset;
    opacity: 0;
    transition: 15s;
}

.spisok_bottom3 {
    list-style-type: none;
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    padding: 0px;
    align-items: center;
    width: 140px;
    height: 80px;
    justify-content: space-evenly;
    border-radius: 25%;
}

.triangle_bottom3:active + .Bottom_menu3 {
    transition: all 1s ease;
    opacity: 1;
}
    .triangle_bottom3:active {
        width: 0px;
        height: 0px;
        border-left: 4px solid transparent;
        border-right: 4px solid transparent;
        border-top: 9px solid #03A9F4;
    }

.Button_Li3:hover + .triangle_bottom3 {
    top: 15px;
}
.Button_Li3:hover {
    height: 40px;
}
.Button_Li4 {
    height: 30px;
    width: 140px;
    background-color: #FF5722;
    border-radius: 0px 0px 25px 25px;
    display: block;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #2b3940;
    transition: all 1s ease;
    position: absolute;
}
.triangle_bottom4 {
    width: 0px;
    height: 0px;
    border-left: 6px solid transparent;
    border-right: 6px solid transparent;
    border-top: 11px solid #03A9F4;
    z-index: 1;
    top: 10px;
    position: absolute;
    margin-left: 115px;
    transition: all 1s ease;
    cursor: pointer;
    transform: scale(10s);
}
.Bottom_menu4 {
    background: #ffffff29;
    height: 80px;
    width: 140px;
    border-radius: 25%;
    margin-top: 45px;
    position: absolute;
    border: outset;
    opacity: 0;
    transition: 15s;
}

.spisok_bottom4 {
    list-style-type: none;
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    padding: 0px;
    align-items: center;
    width: 140px;
    height: 80px;
    justify-content: space-evenly;
    border-radius: 25%;
}

.triangle_bottom4:active + .Bottom_menu4 {
    transition: all 1s ease;
    opacity: 1;
}
    .triangle_bottom4:active {
        width: 0px;
        height: 0px;
        border-left: 4px solid transparent;
        border-right: 4px solid transparent;
        border-top: 9px solid #03A9F4;
    }

.Button_Li4:hover + .triangle_bottom4 {
    top: 15px;
}
.Button_Li4:hover {
    height: 40px;
}
.login {
    display: flex;
    margin: 60px 0px 0px 60px;
    height: 40px;
    width: 230px;
    flex-direction: row-reverse;
    align-items: flex-end;
    position: relative;
}
.Button_login {
    background-color: #BC3513;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 140px;
    height: 45px;
    border-radius: 20px 0px 50px 0px;
    margin: 0px 0px 0px 0px;
    z-index: 1;
    position: absolute;
    right: 0;
    bottom: 0;
    transition: all 4s ease;
}
    .Button_login:hover {
        border-radius: 0px 0px 50px 0px;
        background-color: #956458;
    }

.Button_regust {
    background-color: #956458;
    width: 100px;
    height: 45px;
    border-radius: 0px 0px 50px 0px;
    z-index: 0;
    right: 0;
    opacity: 0;
    position: absolute;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: all 4s ease;
}
.Button_login:hover + .Button_regust {
    right: 60%;
    border-radius: 20px 0px 0px 0px;
    opacity: 1;
}
