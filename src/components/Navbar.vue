<template>
<header>
<nav>
  <label class="brand">uronshala</label>
  <ul>
    <li><a href="#">About</a></li>
    <li><a href="#">Github</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
</header>

</template>

<script>
export default {
  name: 'Navbar',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{
  padding: 0;
  margin: 0;
  text-decoration: none;
  list-style:none;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}  
nav{
  background: #395b64;
  display:flex;
  justify-content: space-around;
  align-items: center;
  height: 80px;
  width: 100%;
  z-index: 10;
}
label.brand{
  color:white;
  font-size: 28px;
  font-weight: 200;
  font-family: 'Poppins', sans-serif;
}
nav ul{
  float:right;
  margin-right:20px;
}
nav ul li{ 
  display: inline-block;
  margin: 0 9px;
}
nav ul li a{
  color:white;
  font-size: 18px;
  font-weight: 300;

}
nav ul li a:hover{
  font-weight:400;
}

@media screen and (max-width: 600px) {
    label.brand{
      font-size: 18px;
    }
      nav ul li a{
        color:white;
        font-size: 16px;
        margin: 0 1px;
      }
      nav ul{
        margin-right: 10px;
      }

}

</style>
