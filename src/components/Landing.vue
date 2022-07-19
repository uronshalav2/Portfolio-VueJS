<template>
  <div class="header-content">
    <div class="container grid-2">
      <div class="column-1">
          <h1 class="header-title">uronshala</h1>
          <p class="text">
            Hello, I'm Uron, Front end Developer.
          </p>
      </div>
      <div class="column-2">
        <img src="../assets/profilepic.png" alt="Profile" class="img-style">
      </div>
    </div>
  </div>
  <div class="container-two">
      <div class="column-1">
        <h1 class="header-title-2">About</h1>
        <p class="text-2">
          Student on Web Programming, worked with <span class="vue">VueJS</span>, <span class="bootstrap">Bootstrap</span>, <span class="html">HTML</span>, <span  class="css">CSS</span>, <span class="js">JS</span>.
        </p>
      </div>
        
    </div>
  <div class="container-three">
      <h1 class="header-title">
        Github
      </h1>
      <div class="card">
        <div class="title">
          <h1>Portfolio-Vuejs</h1>
        </div>
      </div>
    
  </div>
</template>

<script>
export default {
  name: "Landing",
};
</script>

<style scoped>

*{
  font-family: 'Poppins', sans-serif;
}
.vue{
  background-color:#42b883;
  padding: 2px;
}
.bootstrap{
  background-color:#563d7c;
  padding: 2px;
}
.html{
  background-color:#e34c26;
  padding: 2px;
}
.css{
  background-color:#264de4;
  padding: 2px;
}
.js{
  background-color:#f0db4f;
  padding: 2px;
}
.grid-2{
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  align-items: center;
  justify-content: center;
}
.header-conent,.container.grid-2{
  grid-template-columns: 2.5fr 2.5fr;
  min-height: calc(100vh - 6rem);
}
.img-style{
  width: 60%;
  height: 60%;
  background-size: cover;
  background-position: center;
  border-radius: 50%;
  background: #395b64;

}
.header-title{
  color:#395b64;
  font-size: 36px;
  font-weight: 600;
  text-align: left;
}
.text{
  font-size: 24px;
  color:#395b64;
  font-weight: 400;
  text-align: left;
  }

.header-title,.text{
  margin-left: 40px;
}
.container-two{
  display:flex;
  background-color:#395b64;
  min-height: calc(40vh - 6rem);
  justify-content: center;
  align-items: center;

}
.header-title-2{
  color:white;
  font-size: 36px;
  font-weight: 300;
  text-align: center;
}
.text-2{
  font-size: 20px;
  color:white;
  font-weight: 300;
  text-align: center;
  }


.container-three{
  display:flex;
  flex-direction: column;
  min-height: calc(40vh - 6rem);
  justify-content: center;
  align-items: center;

}
</style>
