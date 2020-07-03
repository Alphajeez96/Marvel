<template>
  <div>
    <header>
      <nav>
        <div class="vl"></div>
        <ul class="nav__links">
          <li><a href="#">Services</a></li>
          <span>|</span>
          <li><a href="#">Projects</a></li>
        </ul>
      </nav>

      <a class="logo" href="/"><img src="../../assets/marvel.png" alt="logo" /></a>

      <div class="ttt">
        <nav>
          <div class="vl"></div>
          <ul class="nav__links">
            <li><a href="#">Services</a></li>
            <li><a href="#">Projects</a></li>
          </ul>
        </nav>
      </div>
      <div class="vl-edge" style="color: white;">sss</div>

      <p class="menu cta">Menu</p>
    </header>
    <hr class="border-bottom" />
    <div class="outer-header">
      <ul class="outer__links">
        <li><a href="#">Services</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Projects</a></li>
      </ul>
    </div>

    <div class="overlay">
      <a class="close">&times;</a>
      <div class="overlay__content">
        <a href="#">Services</a>
        <a href="#">Projects</a>
        <a href="#">About</a>
      </div>
    </div>
  </div>
</template>

<style scoped>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 10%;
    background-color: black;
    max-height: 50px;
}

hr {
    border-bottom: 1px solid red;
    position: relative;
    bottom: -1px;
}

.outer-header {
    background: black;
    position: relative;
    bottom: 1px;
    display: flex;
    height: 40px;
    justify-content: center;
    text-align: center;
    flex-direction: row;
    color: white;
}

hr.border-bottom {
    border-bottom: 0.001rem solid gray;
    position: relative;
    font-weight: 100;
    bottom: 1px;
}

.vl {
    border-left: 1px solid gray;
    height: 12vh
}

.vl {
    border-right: 1px solid gray;
    height: 12vh
}

.vl-edge {
    border-right: 1px solid gray;
    height: 10vh;
    color: white;
}

.ttt {
    position: relative;
    left: 150px;
}

.logo {
    cursor: pointer;
}

.nav__links a,
.cta,
.overlay__content a {
    font-family: "Montserrat", sans-serif;
    font-weight: 500;
    color: #edf0f1;
    text-decoration: none;
    font-size: 12px;
}

.nav__links {
    list-style: none;
    display: flex;
    position: relative;
    bottom: 40px;
}

.outer__links {
    list-style: none;
    display: flex;
    position: relative;
    font-size: 12px;
    top: 12px
}

a img {
    position: relative;
    left: 100px
}

.outer__links a {
    font-family: "Montserrat", sans-serif;
    font-weight: 500;
    color: #edf0f1;
    text-decoration: none;
}

.outer__links li {
    padding: 0px 10px;
}

.nav__links span {
    color: white;
}

.nav__links li {
    padding: 0px 10px;
}

.nav__links li a {
    transition: color 0.3s ease 0s;
}

.nav__links li a:hover {
    color: #0088a9;
}

.cta {
    padding: 9px 25px;
    background-color: rgba(0, 136, 169, 1);
    border: none;
    border-radius: 50px;
    cursor: pointer;
    transition: background-color 0.3s ease 0s;
}

.cta:hover {
    background-color: rgba(0, 136, 169, 0.8);
}


/* Mobile Nav */

.menu {
    display: none;
}

.overlay {
    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    left: 0;
    top: 0;
    background-color: #24252a;
    overflow-x: hidden;
    transition: width 0.5s ease 0s;
}

.overlay--active {
    width: 100%;
}

.overlay__content {
    display: flex;
    height: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.overlay a {
    padding: 15px;
    font-size: 36px;
    display: block;
    transition: color 0.3s ease 0s;
}

.overlay a:hover,
.overlay a:focus {
    color: #0088a9;
}

.overlay .close {
    position: absolute;
    top: 20px;
    right: 45px;
    font-size: 60px;
    color: #edf0f1;
}
</style>
