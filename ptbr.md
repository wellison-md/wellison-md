
<style>

abbr {
  text-decoration: none;
  margin-left: 6px;
}
.flex {
  display: flex;
  flex-direction: row;
  word-wrap: wrap;
}

.left {
  justify-content: end;
}

.link {
  cursor: pointer;
  margin-left: 8px;
}

.link:hover {
  opacity: 1;
}

.subtitle {
  font-style: italic;
  font-size: 20px;
  color: #777;
  margin: 0;
}

.unselected {
  opacity: 0.35;
}

p {
  font-size: 18px;
  max-width: 490px;
  text-align: justify;
}

.container {
  max-width: 580px;
  flex-wrap: wrap;
}

.waving-hand {
    display: inline-block;
    animation: wave .6s 3, pause 30s infinite;
    transform-origin: center;
  }

  @keyframes wave {
    0% {
      transform: rotate(0deg);
    }
    50% {
      transform: rotate(-25deg);
    }
    100% {
      transform: rotate(0deg);
    }
  }

</style>



<header class="flex left">
    <a href="./README.md">
      <img class="link unselected" src="./assets/iconus.svg" alt="language: EN-US" />
    </a>
    <img class="link disable" src="./assets/iconbr.svg" alt="language: PT-BR" href="./ptbr.md"/>
</header>


<h1> Olá <span class="waving-hand">👋</span></h1>

<h3> Prazer, sou o Wellison, desenvolvedor web.</h3>
<p class="subtitle"></p>

<p>Entusiasta e apaixonado por criar soluções digitais. Possuo uma sólida formação em desenvolvimento web e experiência em uma variedade de projetos, desde o front-end ao back-end, abrangendo tecnologias como JavaScript, HTML5, CSS3, React.js, Node.js e Java com Spring Boot. Estou comprometido em continuar aprimorando minhas habilidades e estou à procura de novas oportunidades desafiadoras para aplicar meu conhecimento e contribuir para projetos empolgantes. Vamos conversar sobre como posso fazer a diferença em sua equipe?</p>
<br>


<span class="flex container">
  <abbr title="React JS">
    <img alt="React js" src="./assets/reactjs.svg">
  </abbr>

  <abbr title="Redux">
    <img alt="Redux" src="./assets/redux.svg">
  </abbr>

  <abbr title="Jest Testing Library">
    <img alt="Jest" src="./assets/jest.svg">
  </abbr>

  <abbr title="React Testing library">
    <img alt="React-Testing-Library" src="./assets/rtl.svg">
  </abbr>

  <abbr title="Javascript ES6">
    <img alt="Javascript ES6" src="./assets/js.svg">
  </abbr>

  <abbr title="HTML 5">
    <img alt="HTML5" src="./assets/html5.svg">
  </abbr>

  <abbr title="CSS 3">
    <img alt="CSS3" src="./assets/css3.svg">
  </abbr>

  <abbr title="Styled components">
    <img alt="Styled-Components" src="./assets/styled-comp.svg">
  </abbr>

  <abbr title="My Sql">
    <img alt="" src="./assets/mysql.svg">
  </abbr>

  <abbr title="Node.js">
    <img alt="" src="./assets/nodejs.svg">
  </abbr>

  <abbr title="Docker">
    <img alt="" src="./assets/docker.svg">
  </abbr>

  <abbr title="Java">
    <img alt="" src="./assets/java.svg">
  </abbr>

  <abbr title="Spring Boot">
    <img alt="" src="./assets/springboot.svg">
  </abbr>
</span>
