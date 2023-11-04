

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
  <img class="link" src="./assets/iconus.svg" alt="language: EN-US" />
  <a href="ptbr.md">
    <img class="link unselected" src="./assets/iconbr.svg" alt="language: PT-BR"/>
  </a>
</header>

<h1> Hi! <span class="waving-hand">👋</span></h1>

<h3>Nice to meet you, I'm Wellison, a web developer.</h3>
<p class="subtitle"></p>

<p>
Enthusiastic and passionate about creating digital solutions. I have a strong background in web development and experience in a variety of projects, from front-end to back-end, covering technologies like JavaScript, HTML5, CSS3, React.js, Node.js, and Java with Spring Boot. I am committed to continually improving my skills and I am actively seeking new challenging opportunities to apply my knowledge and contribute to exciting projects. Let's discuss how I can make a difference on your team?</p>
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
