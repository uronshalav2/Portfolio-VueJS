<template>
<header>
  <div class="navbar">
    <div class="navbar-brand">
      <h4>uronshala.</h4>
          <div class="navbar-links">
            <ul>
              <li>Home</li>
              <li>About Me</li>
              <li>Links</li>
            </ul>
          </div>
    </div>
  </div>
</header>

</template>

<script>
export default {
  name: 'Navbar',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .navbar {
    display:flex;
    align-content: center;
    height: 80px;
    width: 100%;
    background-color:#0c120c;
  }
  .navbar-brand{
    width: 80%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .navbar-brand h4{
    color:#db3a34;
    font-size: 32px;
    text-align: left;
  }
  .navbar-links{
    color:#db3a34;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .navbar-links ul{
    list-style: none;
  }
  .navbar-links li{
    display: inline-block;
    margin:0px 5px 0px 5px;
    font-size: 28px;
  }
  body{
    margin: 0px !important;
  }
</style>
