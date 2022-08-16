<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">
    <title>Document</title>

    <link rel="stylesheet"type="text/css"href="style.css">
    

</head>


  
    <body>
  <header class="header" id="header">
   
    <nav class="nav container">
<div class="nav__menu"id="nev-menu">
    <img src="https://www.freecodecamp.org/news/content/images/size/w2000/2021/06/w-qjCHPZbeXCQ-unsplash.jpg"alt="" class="nav__image">
<ul class="nav__list">

    <li class="nav__item">
        <a href="#home"class="nav__link">
            <i class='bx bx-home'></i>
        <span class="nav__name">Home</span>
    </a>
    </li>

    <li class="nav__item">
        <a href="#work"class="nav__link">
            <i class='bx bxs-briefcase nav_icon'></i>
        <span class="nav__name">Work</span>
    </a>
    </li>

    <li class="nav__item">
        <a href="#blog"class="nav__link">
            <i class='bx bxl-blogger nav_icon' ></i>
        <span class="nav__name">Blog</span>
    </a>
    </li>

    <li class="nav__item">
        <a href="#about"class="nav__link">
            <i class='bx bxs-user-plus'></i>
        <span class="nav__name">About us</span>
    </a>
    </li>

</ul>

</div>
    </nav>
  </header>
    </body>
</html>
.header{
  position: fixed;
  bottom:0;
  left: 0;
  width: 100%;
  background-color: var(--container-color);
  z-index: var(--z-fixed);
  transition: .4s;
}

@media screen and (max-width:767px){
  .nav__menu{
    position: fixed;
  bottom: 0 ;
    left: 0;
background-color: var(--container-color);
box-shadow: 0 -1px 12px hsla(var(--hue), var(--sat), 15%, 0.15);
 width: 100%;
 height: 4rem;
 padding: 0 1rem;
 display: grid;
 align-items: center;
 border-radius: 1.25rem 1.25rem 0 0;
 transition: .4s;
}
}
.nav__list,.nav__link{
  display: flex;
}
.nav__link{
  flex-direction: column;
  align-items: center;
  row-gap: .25rem;
color: var(--title-color);
font-weight: 600;
  
}
.nav__list{
  list-style: none;
  justify-content: space-around;
}

.nav__name{
  font-size: var(--tiny-font-size);
}
.nav__icon{
  font-size: 1.5rem;
}
a:hover{
  color:blueviolet;
}
