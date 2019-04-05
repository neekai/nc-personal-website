<template>
  <div class="about">

      <div class="hero-image flex-center">
        <div class="hero-text">
          <h2>Get to Know Me as a Person</h2>
          <h1>MY STORY AND PERSONALIOTY</h1>
        </div>
      </div>

    <section class="not-hero">
      <div class="row">
        <div class="col">
          <div class="description-text">
            <h1>My Story</h1>
            <p>I am a first generation Chinese American born in LA. I also spent a significant part of my childhood in Beijing.
              As a result, I am truly able to appreciate both cultures and find the perfect balance between them.
              I celebrate the individual, but also understand the importance of being a team player; I am confident, but not without maintaining humility;
              I am direct, but also very respectful. I am extremely proud of my unique heritage and would not trade it for the world. 
            </p>
          </div>
        </div>
        <div class="col">
          <img src="../assets/nc.jpg" alt="Nick Cai" style="width:100%">
        </div>
      </div>
      <div class="row-2">
        <div class="col">
          <img src="../assets/sing.jpg" alt="Nick Cai" style="width:100%">
        </div>
        <div class="col">
          <div class="description-text">
            <h1>My Hobbies</h1>
            <p>Oh man, there are just so many of them, where do I begin? I love music. I was a part of a choir since going to elementary school in Beijing up until graduating highschool in the US.
              Then I started DJing in college and even got a few songs and mixes on soundcloud. I love to play basketball! People always assumed since I am from LA, my favorite player had to be Kobe, but my actual all time favorite player is Dwyane Wade (He's a baaad man). 
              I started playing when I was 9 and still do till this day because ball is life! I would also love to be able to travel around the world and experience all the different cultures and food.
            </p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <div class="description-text">
            <h1>My Values</h1>
            <p>Family is always first. No amount of money in the world can buy you a loving family. Growing up, I wasn't always the most obedient child. I made countless mistakes, but my family has always had my back through thick and thin.
              My number one goal in life is to make my family proud.
            </p>
          </div>
        </div>
        <div class="col">
          <img src="../assets/family.jpg" alt="Nick Cai" style="width:100%">
        </div>
      </div>
    </section>
  </div>
</template>


<style scoped>
  body, html {
    height: 100%;
  }

  h1 {
    font-size: 2em;
    font-family: 'Open Sans', sans-serif;
  }

  h2 {
    font-size: 1em;
    font-family: 'Open Sans', sans-serif;
    font-style: italic;
    margin-bottom: 1em;
  }

  p {
    padding: 15px;
    font-family: 'Roboto', sans-serif;
    letter-spacing: 1px;
  }

  /* Hero image */

.hero-image {
    min-height: 400px;
    background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url("https://s3-us-west-1.amazonaws.com/guitar-image/home.jpg");
    background-position: center;
    background-size: cover;
    position: relative;
  }

.flex-center {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-content: center;
}

.hero-text {
  color: #fff;
}

.row, .row-2 {
  display: flex;
  justify-content: center;
  align-items: center;
}

.col {
  flex: 50%;
  padding: 5px 0;
}

.row::after {
  content: "";
  clear: both;
  display: table;
}


@media only screen and (min-width:320px) and (max-width: 480px) {
  .row {
    display: block;
  }
  .col {
    padding: 0;
  }

  .row-2 {
    display: block;
    transform: rotate(-180deg);
  }
  .row-2 > div{
    transform: rotate(-180deg);
  }
  .about {
    margin-top: 196px;
    }
  }

@media screen and (min-width: 1024px) {
  .not-hero {
    margin: 0 auto;
    max-width: 65%;
  }
}
</style>
