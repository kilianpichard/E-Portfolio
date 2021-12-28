<script src="../node_modules/rellax/rellax.js"></script>
<template>
  <div>
    <div class="skewed1">
      <div class="blocks current">
        <div class="profile">
          <h2>HI THERE 👋 I'M</h2>
          <h1>PICHARD</h1>
          <h1>Kilian</h1>
          <h3>Web Developper</h3>
        </div>
        <div class="card">
          <pre><span class="grey">1</span>  <span class="red">class</span> <span class="purple">Person {</span></pre>
          <pre><span class="grey">2</span>      <span class="red">constructor</span><span class="purple">() <span class="yellow">{</span></span></pre>
          <pre><span class="grey">3</span>        <span class="blue">this</span>.name = <span class="blue">"Kilian PICHARD"</span>;</pre>
          <pre><span class="grey">4</span>        <span class="blue">this</span>.features = <span class="blue">["STUDENT", "DEV", "FRONT-END"]</span>;</pre>
          <pre><span class="grey">5</span>        <span class="blue">this</span>.age = <span class="red">new Date</span><span class="purple">()</span>.<span class="purple">getFullYear()</span> - 2001;</pre>
          <pre class="yellow"><span class="grey">6</span>      }</pre>
          <pre class="purple"><span class="grey">7</span>  }</pre>
        </div>
      </div>
      <img class="appleProfile" src="@/assets/appleLogo.png" />
    </div>

    <div class="abSpacer"></div>
    <div>
      <h1>About Me</h1>
      <div class="row">
        <div class="col col-6"><img class="pp" src="@/assets/pp.jpg" /></div>
        <div class="col col-6">
          Developer as passionate about the web as about new technologies and
          design. I am particularly attracted to Javascript programming (Vue.JS
          / Node.JS)
        </div>
      </div>
    </div>
    <div class="custom-shape-divider-top-1640347703">
      <svg
        data-name="Layer 1"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 1200 120"
        preserveAspectRatio="none"
      >
        <path d="M1200 0L0 0 892.25 114.72 1200 0z" class="shape-fill"></path>
      </svg>
    </div>
    <div class="skills">
      <h5>Skills & Tools</h5>
      <div>
        technologies I use
        <div class="row">
          <i class="col col-2 devicon-css3-plain-wordmark">CSS 3</i>
          <i class="col col-2 devicon-html5-plain-wordmark">HTML 5</i>
          <i class="col col-2 devicon-bootstrap-plain">BOOTSTRAP</i>
          <i class="col col-2 devicon-php-plain">PHP</i>
          <i class="col col-2 devicon-javascript-plain">JAVASCRIPT</i>
          <i class="col col-2 devicon-typescript-plain">TYPESCRIPT</i>
        </div>
        <div class="row">
          <i class="col col-2 devicon-jquery-plain">JQUERY</i>
          <i class="col col-2 devicon-vuejs-plain">VUEJS</i>
          <i class="col col-2 devicon-nodejs-plain">NODE.JS</i>
          <i class="col col-2 devicon-java-plain">JAVA</i>
          <i class="col col-2 devicon-wordpress-plain">WORDPRESS</i>
          <i class="col col-2 devicon-handlebars-plain">HANDLEBARS</i>
        </div>
      </div>
      <div>
        My Toolbox
        <div class="row">
          <i class="col col-2 devicon-npm-original-wordmark">NPM</i>
          <i class="col col-2 devicon-heroku-plain">HEROKU</i>
          <i class="col col-2 devicon-ionic-original">IONIC</i>
          <i class="col col-2 devicon-git-plain">GIT</i>
          <i class="col col-2 devicon-gitlab-plain">GITLAB</i>
          <i class="col col-2 devicon-bash-plain">BASH</i>
        </div>
        <div class="row">
          <i class="col col-2 devicon-mysql-plain">MYSQL</i>
          <i class="col col-2 devicon-mongodb-plain">MONGODB</i>
          <i class="col col-2 devicon-xd-plain">ADOBE SUITE</i>
          <i class="col col-2 devicon-vscode-plain">VSCODE</i>
          <i class="col col-2 devicon-trello-plain">TRELLO</i>
          <i class="col col-2 devicon-docker-plain">DOCKER</i>
        </div>
      </div>
      <div class="custom-shape-divider-bottom-1640364025">
        <svg
          data-name="Layer 1"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 1200 120"
          preserveAspectRatio="none"
        >
          <path
            d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z"
            class="shape-fill"
          ></path>
        </svg>
      </div>
    </div>

    <div class="projects">
      <div class="project row">
        <div class="col col-6 text">
          <h1>Pram's App</h1>
          <p>
            This is a webapp for the musicien of my music group, converted into
            an ios and android web app, allowing us to manage our concerts,
            create surveys, rehearsal dates , or to calculate mileage costs
            automatically. (Use of several APIs: Youtube / Spotify). Group
            project with
            <a href="">Julien LE PECHEUR</a>
          </p>
          <div class="row tech">
            <i class="devicon-vuejs-plain"></i>
            <i class="devicon-nodejs-plain"></i>
            <i class="devicon-ionic-original"></i>
            <i class="devicon-heroku-plain"></i>
          </div>
        </div>
        <div class="col col-6"><img src="@/assets/iphonesPrams.png" /></div>
        <div class="custom-shape-divider-bottom-1640363614">
          <svg
            data-name="Layer 1"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 1200 120"
            preserveAspectRatio="none"
          >
            <path
              d="M1200 120L0 16.48 0 0 1200 0 1200 120z"
              class="shape-fill"
            ></path>
          </svg>
        </div>
      </div>

      <div class="project row">
        <div class="col col-6"><img src="@/assets/ipadPrams.png" /></div>
        <div class="col col-6 text">
          <h1>Pram's Showcase Website</h1>
          <p>
            This is a showcase website for my music group "Pram's" where you can
            find our videos, photos, musiciens/members. Group project with
            <a target="_blank" href="https://github.com/WarKaa">
              Julien LE PECHEUR
            </a>
          </p>
          <div class="row tech">
            <i class="devicon-vuejs-plain"></i>
            <i class="devicon-gitlab-plain"></i>
            <i class="devicon-heroku-plain"></i>
          </div>
          <v-btn
            class="btn"
            target="_blank"
            href="http://prams.fr/vitrine/accueil"
          >
            <i class="devicon-safari-plain"></i>
            Visit Website
          </v-btn>
        </div>
        <div class="custom-shape-divider-bottom-1640363701">
          <svg
            data-name="Layer 1"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 1200 120"
            preserveAspectRatio="none"
          >
            <path
              d="M1200 120L0 16.48 0 0 1200 0 1200 120z"
              class="shape-fill"
            ></path>
          </svg>
        </div>
      </div>
      <div class="project row">
        <div class="col col-6 text">
          <h1>Schuller Digital Graphic WebSite</h1>
          <p>
            During my internship at Schuller Digital Graphic, I had the
            opportunity to work on many websites, including the new graphic
            charter of the agency. This site allowed me to work on many effects
            like masks or slides
          </p>
          <div class="row tech">
            <i class="devicon-wordpress-plain"></i>
            <i class="devicon-php-plain"></i>
          </div>
          <v-btn
            class="btn"
            target="_blank"
            href="http://survps024.schuller-graphic.com"
          >
            <i class="devicon-safari-plain"></i>
            Visit Website
          </v-btn>
        </div>
        <div class="col col-6"><img src="@/assets/imacSchuller.png" /></div>
        <div class="custom-shape-divider-bottom-1640363811">
          <svg
            data-name="Layer 1"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 1200 120"
            preserveAspectRatio="none"
          >
            <path
              d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z"
              opacity=".25"
              class="shape-fill"
            ></path>
            <path
              d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z"
              opacity=".5"
              class="shape-fill"
            ></path>
            <path
              d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z"
              class="shape-fill"
            ></path>
          </svg>
        </div>
      </div>

      <div class="project row">
        <div class="col col-6"><img src="@/assets/macSamdoc.png" /></div>
        <div class="col col-6 text">
          <h1>Samdoc CIGAR</h1>
          <p>
            This is a showcase website for my music group "Pram's" where you can
            find our videos, photos, musiciens/members. Group project with
            <a>Julien LE PECHEUR</a>
          </p>
          <div class="row tech">
            <i class="devicon-html5-plain"></i>
            <i class="devicon-css3-plain"></i>
            <i class="devicon-javascript-plain"></i>
            <i class="devicon-nodejs-plain"></i>
            <i class="devicon-git-plain"></i>
          </div>
        </div>
      </div>
      <div class="project row">
        <div class="col col-6 text">
          <h1>ShareInstru</h1>
          <p>
            During my internship at Schuller Digital Graphic, I had the
            opportunity to work on many websites, including the new graphic
            charter of the agency. This site allowed me to work on many effects
            like masks or slides
          </p>

          <div class="row tech">
            <i class="devicon-html5-plain"></i>
            <i class="devicon-css3-plain"></i>
            <i class="devicon-php-plain"></i>
            <i class="devicon-git-plain"></i>
          </div>
          <v-btn
            class="btn"
            target="_blank"
            href="https://github.com/kilianpichard/ShareInstru"
          >
            <i class="devicon-github-plain"></i>
            Go to GitHub Repo
          </v-btn>
        </div>
        <div class="col col-6"><img src="@/assets/macShareinstru.png" /></div>
        <div class="custom-shape-divider-bottom-1640363811">
          <svg
            data-name="Layer 1"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 1200 120"
            preserveAspectRatio="none"
          >
            <path
              d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z"
              opacity=".25"
              class="shape-fill"
            ></path>
            <path
              d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z"
              opacity=".5"
              class="shape-fill"
            ></path>
            <path
              d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z"
              class="shape-fill"
            ></path>
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Rellax from 'rellax'
var rellax = new Rellax('.rellax')
import Competences from '@/views/competences.vue'

export default {
  name: 'App',

  data: () => ({
    //
  }),
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;900&display=swap');
* {
  text-decoration: none;
  padding: 0;
  font-family: Calibre-SemiBold, sans-serif;
  margin: 0;
  color: #fafafa;
}
h1 {
  color: #fafafa;
  text-transform: uppercase;
  font-weight: 900;
}

.col {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.card {
  background: #313131;
  color: #fafafa;
  height: 30vh;
  width: 40vw;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 20px;
  position: absolute;
  top: 50%;
  right: 10%;
  transform: translate(0, -50%);
  border-radius: 25px;
  box-shadow: 0px 10px 10px 0px rgba(81, 81, 81, 0.2);
  z-index: 1;
}
.card > pre {
  margin: 5px 0px;
}
.purple {
  color: rgb(167, 128, 223);
}
.red {
  color: rgba(197, 98, 111);
}
.blue {
  color: rgb(118, 179, 248);
}
.yellow {
  color: rgb(207, 207, 74);
}
.grey {
  color: #515151;
}
.logo {
  position: relative;
}
.appleProfile {
  position: absolute;
  top: 40px;
  right: 10%;
  width: 20%;
}
.skewed1 .appleProfile {
  bottom: 15px;
  right: 50px;
  transform: skewY(-4deg) scale(1.5);
  top: unset;
  z-index: 300;
}
.skewed1 .blocks {
  top: 300px;
  height: 95vh;
  transform: skewY(-4deg);
}
.skewed1 {
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  height: 90%;
  background: #6c8885;
  z-index: 0;
  transform: skewY(4deg);
  transform-origin: top right;
}
.custom-shape-divider-top-1640347703 {
  position: relative;
  top: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  line-height: 0;
  margin-top: 100px;
}

.custom-shape-divider-top-1640347703 svg {
  position: relative;
  display: block;
  width: calc(100% + 1.3px);
  height: 50px;
  transform: rotateY(180deg);
}

.custom-shape-divider-top-1640347703 .shape-fill {
  fill: #ffffff;
}
.profile {
  position: absolute;
  top: 50%;
  left: 15%;
  transform: scale(2) translate(0, -50%);
}
.abSpacer {
  height: 100vh;
}

.pp {
  width: 25%;
  border-radius: 500px;
}
.skills {
  height: 100vh;
  background: #6c8885;
  margin-top: -50px;
  padding-top: 100px !important;
  padding: 50px;
  position: relative;
  font-size: 4rem;
}
i::before {
  font-size: 4rem;
  margin-bottom: 15px;
}
i {
  font-size: 1rem;
}
.projects {
  background: #190e44;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.project:nth-child(2n + 1) {
  background: #140b36;
}
.project {
  padding-bottom: 200px;
  padding: 0px 10vw;
  position: relative;
  width: 100vw;
}
.projects h1 {
  position: absolute;
  top: 100px;
}
.project img {
  width: 140%;
}
.col-6.text {
  padding: 50px 100px 10px 100px !important;
  text-align: justify;
  line-height: 1.5rem;
  min-height: 80vh;
}
.text h1 {
  margin-bottom: 50px;
}
.custom-shape-divider-bottom-1640363614 {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  line-height: 0;
  transform: rotate(180deg);
}

.custom-shape-divider-bottom-1640363614 svg {
  position: relative;
  display: block;
  width: calc(100% + 1.3px);
  height: 50px;
}

.custom-shape-divider-bottom-1640363614 .shape-fill {
  fill: #190e44;
}

.custom-shape-divider-bottom-1640363701 {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  line-height: 0;
  transform: rotate(180deg);
}

.custom-shape-divider-bottom-1640363701 svg {
  position: relative;
  display: block;
  width: calc(100% + 1.3px);
  height: 119px;
  transform: rotateY(180deg);
}

.custom-shape-divider-bottom-1640363701 .shape-fill {
  fill: #140b36;
}

.custom-shape-divider-bottom-1640363811 {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  line-height: 0;
  transform: rotate(180deg);
}

.custom-shape-divider-bottom-1640363811 svg {
  position: relative;
  display: block;
  width: calc(100% + 1.3px);
  height: 100px;
  transform: rotateY(180deg);
}

.custom-shape-divider-bottom-1640363811 .shape-fill {
  fill: #190e44;
}
.custom-shape-divider-bottom-1640364025 {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  line-height: 0;
  transform: rotate(180deg);
}

.custom-shape-divider-bottom-1640364025 svg {
  position: relative;
  display: block;
  width: calc(100% + 1.3px);
  height: 65px;
  transform: rotateY(180deg);
}

.custom-shape-divider-bottom-1640364025 .shape-fill {
  fill: #140b36;
}

.project i::before {
  font-size: 2rem !important;
  margin: 20px;
}

.row.tech {
  max-height: 15%;
  margin-top: 50px;
}

.btn {
  background: white !important;
  color: #190e44 !important;
}
.btn * {
  color: #190e44 !important;
}

.col-2 {
  flex: 0 0 16.6666666667%;
  max-width: 16.6666666667%;
}

.row {
  display: flex;
  flex-wrap: wrap;
  flex: 1 1 auto;
  margin-right: -12px;
  margin-left: -12px;
}

.col-6 {
  flex: 0 0 50%;
  max-width: 50%;
}
</style>
