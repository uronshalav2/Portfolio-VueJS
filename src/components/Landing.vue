<template>
  <section>
    <div class="wrapper">
        <div class="card">
            <img class="avatar-img" src="../assets/profilepic.jpeg"/>
            <h2 class="intro-h">I am uronshala</h2>
            <p class="intro-p">Student</p>
        
    </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'Landing'
}
</script>

<style scoped>
    .wrapper{
        display:flex;
        justify-content: center;
        align-items: center;
    }
    .card{
        display: flex;
        flex-direction:column;
        justify-content:center;
        align-items: center;
        margin-top: 100px !important;
        height: 600px;
        width: 740px;
        background: white;
        border-radius: 8px;
        margin: 0 20px;
        box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
    }
    .avatar-img{
        z-index: 1;
        height: 250px;
        width: 250px;
        border-radius: 50%;
        background-size: cover;
        box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
    }
    .intro-h{
        font-family: 'Quicksand' sans-serif !important;
        font-weight: 300;
        color:Black;
    }
</style>
