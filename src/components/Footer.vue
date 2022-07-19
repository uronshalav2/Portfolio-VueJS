<template>
  <footer>
    <div class="footer-top">
        <div class="h1">uronshala</div>
        <li>home</li>
        <li>about</li>
        <li>contact</li>
        <li>github</li>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
    footer{
        border-top:1px solid #395b64;
        height: 20vh;
        width: 100%;
        background-color:white;
    }
    .h1{
        margin-top:20px;
        font-size: 20px;
        font-weight: bolder;
        color:#395b64;
    }
    li{
        display:inline-block;
        padding: 10px;
        color:#395b64;
        font-weight: bolder;
        margin-top: 50px;
        border-bottom: 1px solid #395b64;
        margin-bottom: 40px;
    }
</style>