<script>

export default {
    name: 'AppCrossfitVideosSection',
}

</script>

<template>

    <div class="crossfit-videos-section">
        <div class="text text-center fs-4">
            <button class="white-button">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-play-fill" viewBox="0 0 16 16">
                    <path d="m11.596 8.697-6.363 3.692c-.54.313-1.233-.066-1.233-.697V4.308c0-.63.692-1.01 1.233-.696l6.363 3.692a.802.802 0 0 1 0 1.393z"/>
                </svg>
            </button>
            <h3 class="white-text py-3">Crossfit workout of the day</h3>
            <h5 class="yellow-text pb-2">November 15th, 2019</h5>
            <a href="#" class="white-text">
                View all videos 
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-right" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z"/>
                </svg>
            </a>
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