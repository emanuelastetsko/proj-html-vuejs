<script>

export default {
    name: 'AppCrossfitVideosSection',
}

</script>

<template>

    <div class="crossfit-videos-section">
        <div class="text text-center fs-4">
            <button class="white-button">></button>
            <h3 class="white-text py-3">Crossfit workout of the day</h3>
            <h5 class="yellow-text">November 15th, 2019</h5>
            <a href="#" class="white-text">View all videos -></a>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.crossfit-videos-section{
    background-image: linear-gradient(123deg, rgba(9, 12, 189, 0.553) 0%, rgba(155, 18, 36, 0.9) 100%), url(../assets/img/banner14-2x.jpg);
    background-size: cover;
    min-height: 700px;
    display: flex;
    justify-content: center;
    align-items: center;
}


h3{
    font-size: 2.5em;
}

h5{
    font-size: 1.5em;
}

</style>