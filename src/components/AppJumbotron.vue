<script>

export default {
    name: 'AppJumbotron',
}

</script>

<template>

    <div class="jumbotron">
        <div class="jumbotron-text my-container">
            <h5 class="red-text">Certified fitness professionals</h5>
            <h2>Take control of your health</h2>
            <span>ondulina</span>
            <p class="grey-text">Curabintur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet.</p>
            <button class="bg-blue my-button">++Visit my Youtube channel</button>
            <button class="trasparent-button my-button">Buy Avada today++</button>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.jumbotron{
    background-image: url("../assets/img/slider82x-scaled.jpg");
    background-size: cover;
    min-height: 500px;
    display: flex;
    align-items: center;

    .jumbotron-text{
        color: white;
    }
}

h5{
    font-size: 1.3em;
}

h2{
    padding: 20px 0;
    font-size: 2.7em;
}

p{
    padding: 20px 0;
}

button{
    margin-right: 10px;
}

</style>