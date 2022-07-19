<template>
    <div class="container-two" ref="about">
      <div class="column-1">
        <h1 class="header-title-2">About</h1>
        <p class="text-2">
          Student on Web Programming, worked with <span class="vue">VueJS</span>, <span class="bootstrap">Bootstrap</span>, <span class="html">HTML</span>, <span  class="css">CSS</span>, <span class="js">JS</span>.
        </p>
      </div>
        
    </div>
</template>

<script>
export default {
    name:'About'
}
</script>

<style scoped>
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


</style>