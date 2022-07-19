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

</style>
