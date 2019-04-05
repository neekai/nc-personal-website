<template>
  <div class="container">
    <section class="hero flex-center">
      <h1 class="hero-title">Find Out What I Can Do</h1>
      <h2 class="hero-sub-title">DIG A LITTLE BIT DEEPER</h2>
      <a href="../assets/ncResume.pdf" download>
        DOWNLOAD RESUME
      </a>
    </section>
    <section class="flex-container">
      <div class="box-1">
        <h2>Technologies</h2>
      </div>
      <div class="box-2">
        <h3>Front-End</h3>
        <ul>
          <li>Javascript/jQuery</li>
          <li>HTML5/CSS3</li>
          <li>CSS3</li>
          <li>React.js/Redux</li>
          <li>Vue.js</li>
          <li>Angular.js</li>
          <li>Backbone.js</li>
          <li>Shopify/Liquid</li>
          <li>AJAX</li>
        </ul>
      </div>
      <div class="box-3">
        <h3>Back-End</h3>
        <ul>
          <li>Node.js/Express.js</li>
          <li>MongoDB</li>
          <li>MySQL/Postgres</li>
          <li>RESTful API Development</li>
        </ul>
      </div>
    </section>
    <section class="flex-container-2">
      <div class="flex-container-2-box">
        <h3>Testing/Deployment</h3>
        <ul>
          <li>Jest</li>
          <li>Mocha</li>
          <li>Chai</li>
          <li>Travis CI</li>
          <li>AWS</li>
          <li>Docker</li>
          <li>Artillery.io</li>
          <li>Loader.io</li>
          <li>New Relic</li>
        </ul>
      </div>
      <div class="flex-container-2-box">
        <h3>Developer Tools/Other</h3>
        <ul>
          <li>Git</li>
          <li>Webpack</li>
          <li>Babel</li>
          <li>Mandarin</li>
          <li>Microsoft Office</li>
          <li>Logic Pro</li>
        </ul>
      </div>
    </section>
    <section class="flex-container-3">
      <div class="flex-container-3-box-1">
        <h2>Professional Experience</h2>
      </div>
      <div class="flex-container-3-box-2">
        <h3>Warren Endeavor</h3>
        <h5>Software Engineer, <span>Oct, 2018 - Present</span></h5>
        <p>At Warren Endeavor, I am responsible for developing, implementing, and maintaining high-traffic e-commerce websites and software applications using HTML5, CSS3/SASS, and JavaScript/Liquid. I am instrumental in analyzing the website data, and collaborating on goal-driven solutions with our clients and marketing teams, which include improving the UI/UX that leads to higher conversion rates, increased ROI, increased customer lifetime value, and lower bounce rates. </p>
      </div>
    </section>
    <section class="flex-container-3">
      <div class="flex-container-3-box-1">
        <h2></h2>
      </div>
      <div class="flex-container-3-box-2">
        <h3>Reals Force Inc.</h3>
        <h5>Digital Marketing Coordinator, <span>2017-2018</span></h5>
        <p>While interning at Reals Force, I established and managed our company social media including Facebook, Instagram, Twitter, Wechat, and Weibo. I generated over 5,000 followers on social media by targeting audience and publishing relevant articles/posts. I was also responsible for translating leads and listings from English to Chinese to help expand company presence in the Chinese market.</p>
      </div>
    </section>
    <section class="flex-container-3">
      <div class="flex-container-3-box-1">
        <h2>Software Engineering Applications</h2>
      </div>
      <div class="flex-container-3-box-2">
        <h3>Online Marketplace and Hospitality Service</h3>
        <h5>React.js | Styled Components | Docker.io | MongoDB | Node.js | Grunt.js | AWS</h5>
        <p>This was my first large scale front-end project using React.js and utilizing micro-service architecture. I was responsible for implementing the listing-info component for our online marketplace and hospitality service. I implemented RESTful API design, applied CSS styled components, and utilized Docker.io to compose a consistent developer's environment and speed up code integration and deployment.</p>
      </div>
    </section>
    <section class="flex-container-3">
      <div class="flex-container-3-box-1">
        <h2></h2>
      </div>
      <div class="flex-container-3-box-2">
        <h3>Crowd-Sourced Review Forum</h3>
        <h5>Postgres | MongoDB | Docker.io | Node.js | Artillery.io | Loader.io | New Relic | AWS EC2 | AWS RDS</h5>
        <p>I successfully collaborated with my team to design the schemas and develop RESTful APIs using Node.js to communicate with relational and non-relational databases. I performed numerous stress tests using Loader.io and reduced average query time by eliminating full table scans.
          I have also secured our APIs and built a scalable system by deploying to AWS on EC2 and RDS using Docker, and integrating NGINX to balance our traffic.
        </p>
      </div>
    </section>
    <section class="flex-container-3">
      <div class="flex-container-3-box-1">
        <h2></h2>
      </div>
      <div class="flex-container-3-box-2">
        <h3>I Hate You</h3>
        <h5>MongoDB | Node.js | Express.js | React.js | Semantic UI</h5>
        <p>This was the first Full-Stack web application that I built. I created RESTful Node.js APIs that communicated with Insult API to generate a humorous insult whenever the user entered a name. The user can then save or delete insults based on their preference. 
          This project gave me the opportunity to learn how to connect front-end and back-end, communicate with other web APIs, and persist data. </p>
      </div>
    </section>
    <section class="flex-container-3">
      <div class="flex-container-3-box-1">
        <h2>Education</h2>
      </div>
      <div class="flex-container-3-box-2">
        <h3>Hack Reactor</h3>
        <h5>Advanced Software Engineering immersive, <span>2018</span></h5>
        <br>
        <h3>University of California, Santa Barbara <span>2017</span></h3>
        <h5>B.S. in Financial Mathematics & Statistics</h5>
      </div>
    </section>
  </div>
</template>

<style scoped>

  h1, h2, h3, h5 {
    margin-bottom: 1em;
    font-family: 'Open Sans', sans-serif;
  }

  .hero-title {
    font-style: italic;
    font-size: 1em;
  }

  .hero-sub-title {
    font-size: 2em;
  }

  ul li {
    font-family: 'Roboto', sans-serif;
    padding: 0.5em;
  }

  p {
    font-family: 'Roboto', sans-serif;
    line-height: 1.4;
  }

  /* flex-container */
  .flex-container {
    display: flex;
    margin: 2em;
  }

  .flex-container div, .flex-container-3 div {
    padding: 10px;
  }

  .box-1 {
    flex: 1;
  }

  .box-2 {
    flex: 1;
  }

  .box-3 {
    flex: 1;
  }

  .flex-container-2 {
    display: flex;
    margin: 2em;
    justify-content: flex-end;
  }

  .flex-container-2-box {
    width: 33%;
  }

  .flex-container-3 {
    display: flex;
    justify-content: space-between;
    margin: 2em;
  }


  .flex-container-3-box-1 {
    width: 35%;
  }

  .flex-container-3-box-2 {
    width: 60%;
    text-align: left;
  }

  li {
    list-style: none;
  }

  /* Hero Image */
  .hero {
    min-height: 400px;
    background-image: url("https://images.alphacoders.com/876/thumb-1920-876589.jpg");
    background-size: contain;
    background-position: center;
    text-align: center;
    color: #ffffff;
  }

  .flex-center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  /* download link style */
  a {
    text-decoration: none;
    color: white;
    font-family: 'Open Sans', sans-serif;
    font-size: 1em;
    position: relative;
    border: 3px solid white;
    padding: 1em 2em;
    z-index: 1;
    overflow: hidden;
  }

  a:before {
    content: '';
    background-color: #cf1020;
    top: 0;
    left: 0;
    width: 3em;
    height: 100%;
    position: absolute;
    z-index: -1;
    transform: skew(-15deg);
    animation: moving 1.2s linear infinite;
    transition: all 0.5s;
  }

  @keyframes moving {
    from { left: -3em; }
    to { left: 100%; }
  }

  a:hover:before {
    width: 100%;
    transform: skew(0deg);
    animation: none;
  }


  @media only screen and (min-width:320px) and (max-width: 480px) {
    .flex-container {
      flex-direction: column;
    }
    .flex-container-2 {
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .flex-container-2-box {
      width: 100%;
      padding: 10px;
    }
    .flex-container-3 {
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .flex-container-3-box-1, .flex-container-box-2 {
      width: 100%;
    }
    .hero {
      background-repeat: no-repeat;
      background-size: cover;
    }
  }
  


  

</style>
