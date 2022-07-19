<template>
    <div class="container">
        <h1 class="header-text">Github</h1>
    </div>
    <div class="cards">
            <div class="card">
                <div class="title">
                    <button class="repos" onclick="github">Portfolio-VueJS</button>
                </div>
            </div>
            <div class="card">
                <div class="title">
                    <button class="repos">Wesell-VueJS</button>
                </div>
            </div>
            <div class="card">
                <div class="title">
                    <button class="repos">Wesell-PHP</button>
                </div>
            </div>
        </div>
    
</template>

<script>
export default {
    name:'github'

}
</script>

<style scoped>
    .container{
        display:flex;
        justify-content: center;
        margin-top: 40px;
        width: 100%;
    }
    .header-text{
        color: #395b64;
    }
    .cards{
        display:flex;
        justify-content: center;
        flex-wrap: wrap;
        grid-template-columns: repeat(3, 1fr);
        grid-auto-rows: auto;
        grid-gap: 1rem;
        margin-bottom: 20px;
    }
    .card{
        display:flex;
        background-color: #395b64;
        flex-direction: column;
        justify-content: center;
        margin-top: 15px;
        width: 250px;
        height: 100px;
        border-radius: 12px;
        padding: .5rem;
    }
    .title{
        color:white;
        font-size:18px;
    }
    .repos{
        padding:10px;
        background-color: #395b64;
        border: none;
        outline: none;
        font-size: 18px;
        border-radius: 6px;
        color:white;
    }
</style>