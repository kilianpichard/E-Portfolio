<script src="../node_modules/rellax/rellax.js"></script>
<template>
  <v-app class="app">
    <div class="bg">
      <svg class="blob one rellax" data-rellax-speed="4" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <path fill="#EBF8F8" d="M49.8,-56.4C54.4,-45.2,40.9,-22.6,35.1,-5.7C29.4,11.2,31.5,22.4,26.9,33.6C22.4,44.9,11.2,56.2,-4.8,61C-20.8,65.8,-41.6,64.1,-53,52.8C-64.4,41.6,-66.5,20.8,-62.7,3.8C-58.9,-13.1,-49.2,-26.3,-37.7,-37.4C-26.3,-48.6,-13.1,-57.8,4.7,-62.5C22.6,-67.3,45.2,-67.6,49.8,-56.4Z" transform="translate(100 100)" />
      </svg>
      <svg class="blob two rellax" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <path fill="#EBF8F8" d="M61.1,-50.5C76.9,-45.4,85.5,-22.7,82.3,-3.2C79.1,16.2,63.9,32.5,48.2,41.5C32.5,50.5,16.2,52.3,1.5,50.8C-13.3,49.4,-26.6,44.6,-34,35.6C-41.5,26.6,-43.2,13.3,-44.3,-1.1C-45.3,-15.5,-45.9,-30.9,-38.4,-35.9C-30.9,-41,-15.5,-35.6,3.6,-39.2C22.7,-42.8,45.4,-55.5,61.1,-50.5Z" transform="translate(100 100)" />
      </svg>
      <svg class="blob three rellax"  viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <path fill="#EBF8F8" d="M54.3,-14.4C58.5,-4.9,41.6,14.6,24.2,25.3C6.8,36.1,-11.1,38.1,-21.5,30.3C-31.9,22.6,-34.7,5.2,-29.8,-5.2C-25,-15.7,-12.5,-19.2,6.3,-21.2C25.1,-23.3,50.2,-23.9,54.3,-14.4Z" transform="translate(100 100)" />
      </svg>
    </div>
    <div class="navBar">
      <img
        class="logo"
        src="@/assets/logo.svg"
      />
    </div>
    <v-main class="main">
      <div class="profile">
        <div class="name">
          <h1 class="thin code" v-text="'<'"></h1><h1 class="thin">KILIAN</h1><h1>PICHARD</h1> <h1 class="thin code" v-text="'/>'"></h1>
        </div>
        <div class="avaText">
        <div class="avatar">
          <v-avatar size="250" class="imgAv"><v-img src="@/assets/pp.jpg"></v-img> </v-avatar></div>
        <div class="it">
          <h1 class="thin">IT</h1>
          <h1>STUDENT</h1>
          <h3 class="thin">Caen, France.</h3>
        </div>
        </div>
      </div>
      <div class="firstPart">
        <div class="aboutContainer">
          <h1 class="cat">About Me</h1>
          <div class="underline"></div>
          <h2 class="about">I am currently at IUT Grand Ouest Normandie, at the "IFS" department, to follow my second and last year of DUT Informatique. I had the opportunity to work on several personal / school web projects and I therefore wish to continue my studies in WEB development. I am very attentive, organized, I like teamwork. I always want to learn new languages, new skills, especially through projects by learning by working on them, as I learned Vue.JS. I am very attentive to the design of things, the colors, the layout of the websites, and I pay attention to detail, that's why I rarely use style frameworks like Bootstrap could do.
          </h2>
        </div>

        <div class="skills">
          <div id="first" class="col">
            <div class="imgCont">
              <v-img class="iconSvg" src="@/assets/designer.svg"></v-img>
            </div>
            <h2 class="sTitle">Creation</h2>
            <h3 class="sSub">Creation I've been working on : </h3>
            <p>UI, UX, Logos, Posters, Clips</p>

            <h3 class="sSub">Creating Tools : </h3>
            <p>Adobe Photoshop, Lightroom, Illustrator</p>
            <p>Adobe Premiere Pro, After Effects</p>
            <p>Apple Final Cut Pro, Logic Pro X</p>
            <p>Figma</p>
          </div>
          <div  class="col">
            <div class="imgCont">
              <v-img class="iconSvg" src="@/assets/frontend.svg"></v-img>
            </div>
            <h2 class="sTitle">Web Development</h2>
            <h3 class="sSub">Languages I Speak : </h3>
                <p>HTML 5, CSS 3, JavaScript, PHP, Vue.JS</p>

            <h3 class="sSub">Dev Tools : </h3>
            <p>Oracle, MongoDB, UML</p>
            <p>Heroku</p>
            <p>Git</p>
            <p>Bootstrap, Vuetify</p>
            <p>Cordova/Ionic</p>
          </div>
          <div id="last" class="col">
            <div class="imgCont">
              <v-img class="iconSvg" src="@/assets/binary-code.svg"></v-img>
            </div>
            <h2 class="sTitle">Other</h2>
            <h3 class="sSub">Languages I Speak : </h3>
            <p>Java, C, Basics in Python</p>

            <h3 class="sSub">Dev Tools : </h3>
            <p>SageMath</p>
            <p>Eclipse / IntelliJ</p>
            <p>jUnit / Maven / Jenkins</p>
          </div>
        </div>
      </div>
      <div class="firstPart">
      <div class="aboutContainer">
        <h1 class="cat">My Projects</h1>
        <div class="underline"></div>
        <h2 class="about">I am currently at IUT Grand Ouest Normandie, at the "IFS" department, to follow my second and last year of DUT Informatique. I had the opportunity to work on several personal / school web projects and I therefore wish to continue my studies in WEB development. I am very attentive, organized, I like teamwork. I always want to learn new languages, new skills, especially through projects by learning by working on them, as I learned Vue.JS. I am very attentive to the design of things, the colors, the layout of the websites, and I pay attention to detail, that's why I rarely use style frameworks like Bootstrap could do.
        </h2>
      </div>
      <div class="underline"></div>
      <div class="allProjects">

        <div class="project nameDiv">
          <div class="index">
            <div class="head">
            <img class="projectImg"  src="@/assets/prams.png">
              <h2 class="projectTitle">PRAM'S</h2>
            </div>
            <div class="desc">

              <p class="projectContent">I coded a showcase website for my music group PRAM'S, but also a hidden site, coded with a friend, only accessible by musicians and converted into an ios and android web app, allowing us to manage our concerts, create surveys, rehearsal dates , or to calculate mileage costs automatically. (Use of several APIs: Youtube / Spotify)</p>
              <div class="language">
                <p class="tech">Technologies Used</p>
                <p>Vuetify, MongoDB, Capacitor/Ionic, Heroku, Git</p>
                <a class="link" href="http://www.prams.fr" target="_blank">www.prams.fr</a>
              </div>
            </div>
          </div>
        </div>
        <div class="project nameDiv">
          <div class="zI">
          <div class="head">
          <img class="projectImg" src="@/assets/armelle.png">
            <h2 class="projectTitle">ARMELLE BEAUTÉ</h2>
          </div>
          <div class="desc">

            <p class="projectContent">I created with the CMS "JIMDO" a showcase site of product presentation and services of the beauty institute "Armelle Beauté"</p>
            <div class="language">
              <p class="tech">Technologies Used</p>
              <p>CMS Jimdo</p>
              <a class="link" href="http://www.armellebeaute.fr" target="_blank">www.armellebeaute.fr</a>
            </div>

          </div>
          </div>
        </div>
        <div class="project">
          <div class="zI">
          <div class="head">
          <img class="projectImg"  src="@/assets/tdf.png">
            <h2 class="projectTitle">Tour de France</h2>
          </div>
          <div class="desc">
            <p class="projectContent">We worked in groups of 4 on a project based on the "Tour de France", this project was entirely in PHP and on an ORACLE database. We had to retrieve several information, create some, like: adding cyclists, retrieving information / rankings</p><div class="language">
            <p class="tech">Technologies Used</p>
            <p>PHP, Oracle</p>
          </div>
          </div>
          </div>
        </div>
        <div class="project">
          <div class="zI">
            <div class="head">
              <img class="projectImg"  src="@/assets/indep.png">
                <h2 class="projectTitle">Indépendante de Messei</h2>
            </div>

          <div class="desc">

            <p class="projectContent">I coded a site for my other band, "L'Indépendante de Messei". This brings together our information, next concert dates, photo gallery</p>
            <div class="language">
              <p class="tech">Technologies Used</p>
              <p>HTML 5, CSS 3</p>
              <a class="link" href="http://www.indépendante-messei.fr" target="_blank">www.indépendante-messei.fr</a>
            </div>
          </div>
          </div>
        </div>
      </div>
      </div>
    </v-main>
  </v-app>
</template>

<script>
import Rellax from 'rellax';
var rellax = new Rellax('.rellax');

export default {

  name: "App",

  data: () => ({
    //
  })
};
</script>


<style>
*{
  text-decoration: none;
  padding: 0;
  margin: 0;
}
.thin{
  font-weight: lighter;
}

.navBar{
  color:white;
  display: flex;
  flex-wrap: wrap;
  padding:15px;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  width: 100%;
  position: relative;
  background: #F9F9F9;
}
.logo{
  height: 40px;
  width: 40px;
}
.code{
  color:lightseagreen;
}
.name{
  font-size: 40px;
  margin-left: 30px;
  z-index: 15;
}
.cat{
  font-size: 40px;
  margin: auto;
  height: 60px;
}
.avatar{
  border: 3px solid lightseagreen;
  padding:10px;
  border-radius: 500px;
  transition: all .5s ease;
}
.avatar:hover{
  padding:2px;
  border: 11px solid lightseagreen;
  transition: all .5s ease;
}
.avaText{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}
.it{
  margin:20px;
  color: lightseagreen;
}
.profile{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;
}
.blob{
  position: absolute;
  opacity: 0.7;
  z-index: 10;
}
.one{
  width: 60vw;
  top:0;

}
.two{
  width: 60vw;
  right: 0;
  top:100vh;
}
.three{
  width: 100vw;
  right: 25vw;
  top:220vh;
}


.skill{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}
.skill>p{
  padding-top:7px;
}
.skill>img{
  height: 60px;
}
.sTitle{
  color: #232323;
  font-size: 25px;
}
.sSub{
  color: lightseagreen;
  font-weight: normal;
  margin: 5px;
}
.col{
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  z-index: 15;
}
.iconSvg{
  height: 48px !important;
}
.imgCont{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  height: 80px;
}
.skills{
  box-shadow: 0px 0px 30px 4px rgba(0,0,0,0.10);
  margin: auto;
  display: flex;
  flex-wrap: wrap;
  border:1px solid lightseagreen;
  border-radius: 20px;
  width: 80vw;
  position: absolute;
  top:80vh;
  left:10vw;
  background: #F9F9F9;
}
#first{
  border-right: 1px solid lightseagreen;
}
#last{
  border-left: 1px solid lightseagreen;
}
.aboutContainer{
  background: lightseagreen;
  color: white;
  padding: 150px 50px 300px 50px;
}
.about{
  text-align: justify;
}
.firstPart{
  position: relative;
  padding-bottom: 400px;
}
.underline{
  width: 10%;
  border-top: 2px solid white;
  margin-bottom: 20px;
}
.project{
  background: white;
  z-index: 0;
  display: flex;
  align-items: center;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: flex-start;
  box-shadow: 0px 0px 30px 4px rgba(0,0,0,0.10);
  width: 30vw;
  height: 450px;
  padding:20px;
  z-index: 15;
  border-radius: 20px;
  margin: 10px;
  transition: all .3s ease;
}
.link{
  color:lightseagreen !important;
  font-size: 20px;
}
.link:visited{
  color: lightseagreen !important;
}
.desc{
  height: 100px;
}
.project:hover{
  box-shadow: 0px 15px 30px 4px rgba(0,0,0,0.15);
}
.language{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.tech{
  color:lightseagreen;
}

.head{
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom:10px;

}
.head>h2{
  font-weight: normal;
  width: 200px;
  text-align: center;
  text-transform: uppercase;
}
.allProjects{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;
  position: absolute;
  top:90vh;
}
.projectContent{
  text-align: justify;
  height: 180px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.tech{
  font-size: 20px;
}
.projectImg{
  height: 100px;
  width: 100px;
  border-radius: 500px;
}

</style>
