<template>
  <header>
    <div class="container" id="myHeader">
      <router-link to="/">
        <img src="../../assets/ncLogo.png" alt="Nick Cai">
      </router-link>
      <div id="header-right">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/resume">Resume</router-link>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  methods: {
  }
}


</script>

<style scoped>
  
  .container {
    overflow: hidden;
    background-color: rgb(45,45,45,0.98);
    padding: 8px 5px;
    position: fixed;
    left: 0;
    top: 0;
    width: 100%;
    z-index: 200;
  }

  img {
    width: 30px;
  }

  .container a {
    text-decoration: none;
    float: left;
    text-align: center;
    padding: 12px;
    font-size: 14px;
    border-radius: 4px;
    position: relative;
    color: white;
  }

  #header-right > a:before {
    content: "";
    position: absolute;
    width: 100%;
    height: 2px;
    bottom: 0;
    left: 0;
    background-color: #cf1020;
    visibility: hidden;
    transform: scaleX(0);
    transition: all 0.4s ease-in-out 0s;
  }


  #header-right > a:hover:before {
    visibility: visible;
    transform: scaleX(1);
  }

  #header-right a:hover {
    color: #C8C8C8;
  }

  #header-right {
    float: right;
  }

  .sticky {
    position: fixed;
    top: 0;
    width: 100%;
  }



  @media screen and (max-width: 500px) {
    .container a {
      float: none;
      display: block;
      text-align: left;
    }

    #header-right {
      float: none;
    }
  }
</style>

