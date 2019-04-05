<template>
  <div class="container">
    
    <ul class="lighting">
      <li>N</li>
      <li>I</li>
      <li>C</li>
      <li>K</li>
       &nbsp;
      <li>C</li>
      <li>A</li>
      <li>I</li>
    </ul>

    <ul class="smokey">
      <li>S</li>
      <li>O</li>
      <li>F</li>
      <li>T</li>
      <li>W</li>
      <li>A</li>
      <li>R</li>
      <li>E</li>
       &nbsp;
      <li>E</li>
      <li>N</li>
      <li>G</li>
      <li>I</li>
      <li>N</li>
      <li>E</li>
      <li>E</li>
      <li>R</li>
    </ul>
    
  </div>
</template>

<script>


export default {
  name: 'Home',
  components: {
  }
}
</script>

<style scoped>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  .container {
    font-family: Arial, Helvetica, sans-serif;
    height: 100vh;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    background-color: #272727;
  }

  ul {
    margin: 0;
    padding: 0;
    display: flex;
  }

  ul li {
    list-style: none;
  }

  .lighting li {
    color: #484848;
    font-size: 80px;
    letter-spacing: 15px;
    animation: lighting 1.4s linear infinite;
  }

  .lighting {
    margin-bottom: 2em;
  }

  @keyframes lighting {
    0% {  color: #484848;
          text-shadow: none;
       }
    90% {  color: #484848;
          text-shadow: none;
       }
    100% {  color: #fff900;
            text-shadow: 0 0 7px #fff900, 0 0 50px #ff6c00;
         }
  }

  .lighting li:nth-child(1) {
    animation-delay: 0;
  }

  .lighting li:nth-child(2) {
    animation-delay: 0.1s;
  }

  .lighting li:nth-child(3) {
    animation-delay: 0.2s;
  }

  .lighting li:nth-child(4) {
    animation-delay: 0.4s;
  }

  .lighting li:nth-child(5) {
    animation-delay: 0.8s;
  }
  .lighting li:nth-child(6) {
    animation-delay: 0.8s;
  }
  .lighting li:nth-child(7) {
    animation-delay: 0.8s;
  }

  @keyframes color {
    from {
      color: #484848;
    }
    to {
      color: #fff;
    }
  }

 .smokey li {
    color: #fff;
    letter-spacing: 5px;
    transition: 2s;
    animation: color 2.4s ease-in-out;
  }

  .smokey:hover li {
    transform: rotate(-45deg) translateY(200px);
    opacity: 0;
    filter: blur(20px);
  }

  .smokey li:nth-child(1) {
    transition-delay: 0;
    animation-delay: 0;
  }
  
  .smokey li:nth-child(2) {
    transition-delay: 0.1s;
    animation-delay: 0.1s;
  }

  .smokey li:nth-child(3) {
    transition-delay: 0.2s;
    animation-delay: 0.3s;
  }
  
  .smokey li:nth-child(4) {
    transition-delay: 0.3s;
    animation-delay: 0.4s;
  }

  .smokey li:nth-child(5) {
    transition-delay: 0.4s;
    animation-delay: 0.5s;
  }
  
  .smokey li:nth-child(6) {
    transition-delay: 0.5s;
    animation-delay: 0.6s;
  }
  
  .smokey li:nth-child(7) {
    transition-delay: 0.6s;
    animation-delay: 0.7s;
  }
  
  .smokey li:nth-child(8) {
    transition-delay: 0.7s;
    animation-delay: 0.8s;
  }
  
  .smokey li:nth-child(9) {
    transition-delay: 1.3s;
    animation-delay: 0.9s;
  }
  
  .smokey li:nth-child(10) {
    transition-delay: 1.4s;
    animation-delay: 1s;
  }

  .smokey li:nth-child(11) {
    transition-delay: 1.5s;
    animation-delay: 1.1s;
  }
  
  .smokey li:nth-child(12) {
    transition-delay: 1.6s;
    animation-delay: 1.2s;
  }

  .smokey li:nth-child(13) {
    transition-delay: 1.7s;
    animation-delay: 1.3s;
  }
  
  .smokey li:nth-child(14) {
    transition-delay: 1.8s;
    animation-delay: 1.4s;
  }
  .smokey li:nth-child(15) {
    transition-delay: 1.9s;
    animation-delay: 1.5s;
  }
  
  .smokey li:nth-child(16) {
    transition-delay: 2s;
    animation-delay: 1.6s;
  }

  @media only screen and (min-width:320px) and (max-width: 480px) {
    .lighting li {
      font-size: 4em;
    }
    .smokey li {
      font-size: 1em;
    }
  }

</style>
