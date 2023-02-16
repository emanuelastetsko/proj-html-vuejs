<script>

export default {
    name: 'AppSubscriptionSection',
}

</script>

<template>

    <div class="subscription-section">
        <div class="my-container-special text-center fs-5">
            <h2 class="white-text">"I've failed over and over again in my life. And that is why I succeed."</h2>
            <span class="yellow-text">!Ondulina!</span>
            <p class="white-text py-3">Arcu auctor nisl, congue sit nisi tincidunt eget proin. In lacinia lacus donec sed massa in ipsum eros, tristique. Gravida suspendisse etiam in iaculis</p>
            <button class="bg-blue my-button">Buy Avada today ></button>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.subscription-section{
    background-image: linear-gradient(0deg, rgba(10,12,41, 0.8) 39%, rgba(6,6,7,0) 100%), url(../assets/img/banner2-2x.jpg);
    background-size: cover;
    min-height: 700px;
    display: flex;
    align-items: center;
}

h2{
    font-size: 3em;
}

</style>