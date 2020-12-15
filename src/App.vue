<template>
  <v-app class="app">
    <div class="appBar">
      <div class="navBar">
        <div class="flexRow nameDiv">
          <h1 class="thin code" v-text="'<'"></h1><h1 class="thin firstname">KILIAN</h1><h1 class="name">PICHARD</h1> <h1 class="thin code" v-text="'/>'"></h1>
        </div>
        <img
          class="imgLogo"
          src="@/assets/kilian.gif"
        />
        <div class="nav">
          <a href="#about"><span class="point">.</span><span class="redt">aboutMe</span><span class="point">()</span></a>
          <a href="#skills"><span class="point">.</span><span class="aqua">skills</span><span class="point">()</span></a>
          <a href="#projects"><span class="point">.</span><span class="pinkAC">projects</span><span class="point">()</span></a>
        </div>
      </div>
    </div>
    <v-main class="main">
      <transition name="bounce">
        <Profile></Profile>
      </transition>
      <div class="title" id="about">
        <h1 class="redC" v-text="'<'+'h1'+'>'"></h1>
        <h1 class="name">About Me</h1>
        <h1 class="redC" v-text="'<'+'h1'+'>'"></h1>
      </div>
      <h2 class="about">I am currently at IUT Grand Ouest Normandie, at the "IFS" department, to follow my second and last year of DUT Informatique. I had the opportunity to work on several personal / school web projects and I therefore wish to continue my studies in WEB development. I am very attentive, organized. I always want to learn new languages, new skills, especially through projects by learning by working on them, as I learned Vue.JS. I am very attentive to the design of things, the colors, the layout of the websites, and I pay attention to detail, that's why I rarely use style frameworks like Bootstrap could do.
      </h2>
      <div class="title" id="skills">
        <h1 class="aquaC" v-text="'<'+'h1'+'>'"></h1>
        <h1 class="name">Skills</h1>
        <h1 class="aquaC" v-text="'<'+'h1'+'>'"></h1>
      </div>
      <div class="skills">
        <div class="title h">
          <h2 class="code" v-text="'<'+'h2'+'>'"></h2>
          <h2 class="name">Web Programming</h2>
          <h2 class="code" v-text="'<'+'h2'+'>'"></h2>
        </div>
        <div class="row">
        <div class="skill">
          <img src="@/assets/html.png"><p>HTML 5</p>
        </div>
        <div class="skill">
          <img src="@/assets/css.png"><p>CSS 3</p>
        </div>
        <div class="skill">
          <img src="@/assets/js.png"><p>JavaScript</p>
        </div>
          <div class="skill">
            <img src="@/assets/bootstrap.png"><p>Bootstrap</p>
          </div>
        <div class="skill">
          <img src="@/assets/php.png"><p>PHP</p>
        </div>
        <div class="skill">
          <img src="@/assets/vue.png"><p>Vue.JS</p>
        </div>
        <div class="skill">
          <img src="@/assets/vuetify.png"><p>Vuetify</p>
        </div>
        </div>
      </div>
      <div class="skills">
        <div class="title h">
          <h2 class="code" v-text="'<'+'h2'+'>'"></h2>
          <h2 class="name">Other Programming Languages</h2>
          <h2 class="code" v-text="'<'+'h2'+'>'"></h2>
        </div>
        <div class="row">
          <div class="skill">
            <img src="@/assets/java.png"><p>JAVA</p>
          </div>
          <div class="skill">
            <img src="@/assets/c.png"><p>C</p>
          </div>
          <div class="skill">
            <img src="@/assets/python.png"><p>Basics in PYTHON</p>
        </div>
      </div>
      </div>
      <div class="skills">
        <div class="title h">
          <h2 class="code" v-text="'<'+'h2'+'>'"></h2>
          <h2 class="name">DataBases</h2>
          <h2 class="code" v-text="'<'+'h2'+'>'"></h2>
        </div>
        <div class="row">
          <div class="skill">
            <img src="@/assets/oracle.png"><p>Oracle</p>
          </div>
          <div class="skill">
            <img src="@/assets/mongo.png"><p>MongoDB</p>
          </div>
          <div class="skill">
            <img src="@/assets/uml.png"><p>UML</p>
          </div>
        </div>
      </div>
      <div class="skills">
        <div class="title h">
          <h2 class="code" v-text="'<'+'h2'+'>'"></h2>
          <h2 class="name">Softwares</h2>
          <h2 class="code" v-text="'<'+'h2'+'>'"></h2>
        </div>
        <div class="row">
          <div class="skill">
            <img src="@/assets/adobe.svg"><p>Adobe Suite</p>
          </div>
          <div class="skill">
            <img src="@/assets/office.png"><p>Office</p>
          </div>
        </div>
      </div>
      <div class="title" id="projects">
        <h1 class="pinkC" v-text="'<'+'h1'+'>'"></h1>
        <h1 class="name">My Projects</h1>
        <h1 class="pinkC" v-text="'<'+'h1'+'>'"></h1>
      </div>
      <div class="allProjects">
        <div class="project nameDiv">
        <v-img src="@/assets/prams.png"
        class="projectImg"></v-img>
          <div class="desc">
            <h2 class="projectTitle">Website - PRAM'S</h2>
            <p class="projectContent">I coded a showcase website for my music group PRAM'S, but also a hidden site, coded with a friend, only accessible by musicians and converted into an ios and android web app, allowing us to manage our concerts, create surveys, rehearsal dates , or to calculate mileage costs automatically. (Use of several APIs: Youtube / Spotify | Use of git)</p>
            <div class="language">
              <img src="@/assets/vuetify.png" class="languageImg"><p>Vuetify</p>
              <img src="@/assets/mongo.png" class="languageImg"><p>MongoDB</p>
              <img src="@/assets/capacitor.png" class="languageImg"><p>Capacitor</p>
              <img src="@/assets/heroku.png" class="languageImg"><p>Heroku</p>
            </div>

          </div>
          <a href="http://prams.fr/vitrine/accueil" target="_blank"><img class="redirect" src="@/assets/redirect.png" ></a>
        </div>
          <div class="project nameDiv">
          <v-img src="@/assets/armelle.png"
                 class="projectImg"></v-img>
          <div class="desc">
            <h2 class="projectTitle">Website - ARMELLE BEAUTÉ</h2>
            <p class="projectContent">I created with the CMS "JIMDO" a showcase site of product presentation and services of the beauty institute "Armelle Beauté"</p>
            <div class="language"><img src="@/assets/jimdo.png" class="languageImg"></div>

          </div>
            <a href="http://armellebeaute.fr" target="_blank"><img class="redirect" src="@/assets/redirect.png"></a>
        </div>
          <div class="project nameDiv">
            <v-img src="@/assets/tdf.png"
                   class="projectImg"></v-img>
            <div class="desc">
              <h2 class="projectTitle">School Project - Tour de France</h2>
              <p class="projectContent">We worked in groups of 4 on a project based on the "Tour de France", this project was entirely in PHP and on an ORACLE database. We had to retrieve several information, create some, like: adding cyclists, retrieving information / rankings</p><div class="language">
                <img src="@/assets/php.png" class="languageImg"><p>PHP</p>
              <img src="@/assets/oracle.png" class="languageImg"><p>Oracle</p>
              </div>
            </div>
        </div>
        <div class="project nameDiv">
          <v-img src="@/assets/indep.png"
                 class="projectImg"></v-img>
          <div class="desc">
            <h2 class="projectTitle">Website - INDÉPENDANTE DE MESSEI</h2>
            <p class="projectContent">I coded a site for my other band, "L'Indépendante de Messei". This brings together our information, next concert dates, photo gallery</p>
            <div class="language">
              <img src="@/assets/html.png" class="languageImg"><p>HTML 5</p>
              <img src="@/assets/css.png" class="languageImg"><p>CSS 3</p>
            </div>
          </div>
          <a href="http://indépendante-messei.fr" target="_blank"><img class="redirect" src="@/assets/redirect.png"></a>
        </div>
      </div>
    </v-main>
  </v-app>
</template>

<script>
import Profile from "@/components/Profile";

export default {
  name: "App",

  components: {Profile},

  data: () => ({
    //
  })
};
</script>


<style>
p,h2{
  color:white;
}
*{
  text-decoration: none;
}
.thin{
  font-weight: lighter;
}
.main,.appBar{
  background: url("../src/assets/fond.png");
}
.appBar{
  color:white;
  padding:15px;
}
.navBar{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 100%;
}
.imgLogo{
  height: 40px !important;
  width: 40px !important;
}
.flexRow{
  display: flex;
  align-items: center;
}
a{
  color:lightseagreen !important;
  font-weight: bolder;
  background: transparent !important;
  transition: all .3s ease !important;
}
a:hover .point{
    color: white !important;
  transition: all .3s ease;
}
a:hover .redt,.redC{
  color: red !important;
  transition: all .3s ease;
}
a:hover .aqua,.aquaC{
  color: aqua !important;
  transition: all .3s ease;
}
a:hover .pinkAC,.pinkC{
  color:hotpink !important;
  transition: all .3s ease;
}
a:hover .purplet{
  color: magenta !important;
  transition: all .3s ease;
}
.nav{
  width: 350px;
  display: flex;
  justify-content: space-between;
}
.code{
  color:lightseagreen !important;
  transition: all .3s ease;
}
.nameDiv:hover .firstname{
  color:lightseagreen !important;
  transition: all .3s ease;
}
.nameDiv:hover .name{
  color:lightseagreen !important;
  transition: all .3s ease;
 }
.title{
  display: flex;
  margin:20px 0px;
}
h2.about{
  margin:10px;
}
.main{
  padding: 10px !important;
}
.name{
  color:white;
}
.projectImg{
  border-radius: 30px;
  width: 200px;
  height: 200px;
  margin-right: 10px;
}
.project{
  margin-top:20px;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 700px !important;
}
.projectContent{
  text-align: justify;
  padding-right: 40px;
  max-width: 500px;
}

.language{
  display: flex;
  align-items: start;
  justify-content: start;
}
.languageImg{
  max-height: 20px;
  margin:5px;
  margin-left: 10px;
}
.allProjects{
  display: flex;
  align-items: center;
  justify-content: space-around;
  flex-wrap: wrap;
}
.language>p{
padding-top:4px;
}
.project{
  border-radius: 20px;
  background: rgba(100,100,100,0.3);
  padding:20px;
  height: 300px;
}
.h{
  margin-left: 20px;
}
.skill{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 200px;

}
.skill>img{
  height: 50px;
}
.skill>p{
  padding-top:10px;
  margin-left: 5px;
}
.row{
  display: flex;
  justify-content: center;
  border-radius: 20px;
  background: rgba(100,100,100,0.3);
  padding:20px 0px;
  margin:20px 0px;
}
.about{
  border-radius: 20px;
  background: rgba(100,100,100,0.3);
  padding:20px;
  margin:20px 0px;
  text-align: justify;
}
.project{
  position: relative;
}
.redirect{
  height: 50px;
  position: absolute;
  bottom: 7px;
  right: 10px;
}
</style>
