<template>
  <div id="app">
    <div id="nav">
    </div>
    <router-view/>
  </div>
</template>

<style>
@font-face {
  font-family: "FuturaDemiC";
  src: local("FuturaDemiC"),
   url(./assets/fonts/FuturaDemiC/FuturaDemic.otf) format("truetype");
}
@font-face {
  font-family: "FuturaLightC";
  src: local("FuturaLightC"),
   url(./assets/fonts/FuturaLightC/FuturaLightC.otf) format("truetype");
}
@font-face {
  font-family: "FuturaFuturisC";
  src: local("FuturaFuturisC"),
   url(./assets/fonts/FuturaFuturisC/FuturaFuturisC.otf) format("truetype");
}
@font-face {
  font-family: "FuturaBookC";
  src: local("FuturaBookC"),
   url(./assets/fonts/FuturaBookC/FuturaBookC.otf) format("truetype");
}

body {
  background-color: #F2F2F4;
  margin: 0;
}

#app {
  font-family:FuturaLightC, regular;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  
}

a {
  font-family:FuturaLightC;
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  color: #FFFFFF;
  align-items: center;
  display: flex;
    
}
h1 {
  font-family: FuturaFuturisC;
font-style: normal;
font-weight: 700;
font-size: 69.23px;
line-height: 69px;
text-transform: uppercase;
color: #FFFFFF;
margin: 0 auto;
}
p {
  font-family: FuturaBookC;
font-style: normal;
font-weight: 400;
font-size: 22px;
line-height:29px;
color: #FFFFFF;
margin: 0;
}
h2 {
  font-family: 'FuturaDemiC';
font-style: normal;
font-weight: 600;
font-size: 24px;
line-height: 28px;
/* identical to box height, or 117% */


color: #333333;
}
</style>
