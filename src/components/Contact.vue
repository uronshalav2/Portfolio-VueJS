<template>
  <div class="contact-wrapper">
       <h1 class="titleC">Contact</h1> 
    <div class="form">
        <form action="#">
            <input type="text" name="" placeholder="Email"/>
            <br>
            <input type="text" name="" placeholder="Name"/>
            <br>
            <textarea rows="4" name="" placeholder="Message"/>
            <button type="submit" class="submitbtn">Send</button>
        </form>
            
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.contact-wrapper{
    display:flex;
    flex-direction:column;
    justify-content: center;
    width:100%;
    background-color: #395b64;
}
.titleC{
    margin-top: 20px;
    margin-bottom: 20px;
    color:white;
}
.form{
    display: flex;
    align-items: center;
    justify-content: center;
    padding-bottom: 30px;
}
form{
    display:flex;
    flex-direction: column;
    width: 500px;
    background-color: white;
    margin:0 10px;
    padding: 50px;
    height: 400px;
    border-radius: 12px;
}
input{
    padding: 5px;
    outline: none;
    border:none;
    border-bottom: 1px solid #395b64;
    margin: 10px;
}
textarea{
    padding: 5px;
    margin:10px;
    outline:none;
    border:none;
    border-bottom: 1px solid #395b64;
    resize: none;
}
.submitbtn{
    padding: 10px;
    width: 100px;
    align-self: center;
    background-color: #395b64;
    border:none;
    margin-top: px;
    color:white;
    font-size: 16px;
    cursor:pointer;
    border-radius: 5px;
    margin:5px;
}
</style>