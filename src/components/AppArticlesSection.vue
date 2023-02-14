<script>

export default {
    name: 'AppArticlesSection',
}

</script>

<template>

    <div class="articles-section my-3 py-5">
        <div class="my-container">
            <div class="description">
                <h6>Latest articles</h6>
                <a href="#" class="black-text">Read all articles ></a>
            </div>
            <div class="articles-preview">
                <div class="row">
                    <div class="col-4">
                        <img src="../assets/img/blog4-2x-1200x773.jpg" alt="Blog 1" class="img-fluid">
                        <h5>The best protein shake</h5>
                        <span class="grey-text">By admin | November 26th, 2019 | Gym</span>
                    </div>
                    <div class="col-4">
                        <img src="../assets/img/blog1-2x-1200x773.jpg" alt="Blog 2">
                        <h5>Ultimate cardio workout</h5>
                        <span class="grey-text">By admin | November 26th, 2019 | Gym</span>
                    </div>
                    <div class="col-4">
                        <img src="../assets/img/blog3-2x-1200x773.jpg" alt="Blog 3">
                        <h5>New juices available now</h5>
                        <span class="grey-text">By admin | November 26th, 2019 | Gym</span>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.description{
    display: flex;
    justify-content: space-between;
}

img{
    width: 450px;
    height: auto;
}


</style>