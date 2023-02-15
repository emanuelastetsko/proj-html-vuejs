<script>

export default {
    name: 'AppJumbotron',
}

</script>

<template>
    <div class="first-big-section">
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
        <div class="motivational-section">
            <div class="my-container my-cards">
                <div class="row">
                    <div class="col-4 my-card">
                        <img src="../assets/img/service6-2x.jpg" alt="First image" class="card-img">
                        <div class="text-card">
                            <span class="white-text d-block">!Ondulina!</span>
                            <h5 class="white-text">Crossfit workout</h5>
                            <h6 class="yellow-text">Push your limits</h6>
                        </div>
                    </div>
                    <div class="col-4 my-card">
                        <img src="../assets/img/box1-2x.jpg" alt="Second image" class="card-img">
                        <div class="text-card">
                            <span class="white-text d-block">!Ondulina!</span>
                            <h5 class="white-text">New gym apparel</h5>
                            <h6 class="yellow-text">Look good, feel good</h6>
                        </div>
                    </div>
                    <div class="col-4 my-card">
                        <img src="../assets/img/box3-2x.jpg" alt="Third image" class="card-img">
                        <div class="text-card">
                            <span class="white-text d-block">!Ondulina!</span>
                            <h5 class="white-text">Team training</h5>
                            <h6 class="yellow-text">Find a partner</h6>
                        </div>
                    </div>     
                </div>
            </div>
            <div class="my-container-special text-center pt-5">
                <h2 class="white-text">"How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."</h2>
                <span class="yellow-text">!Ondulina!</span>
                <div class="user-info pt-4 pb-5">
                    <img src="../assets/img/avatar-1-2x.jpg" alt="Profile pic" class="profile-pic">
                    <span class="p-3">Brad Johnson</span>
                    <span class="grey-text">Las Vegas</span>
                </div>
            </div>
        </div>
        <div class="youtube-section">
            <div class="youtube-section-top">
                <div class="row">
                    <div class="col-6">
                        <img src="../assets/img/service15-2x.jpg" alt="Video preview" class="big-video-preview">
                    </div>
                    <div class="col-6 py-5 px-5">
                        <h5 class="blue-text">Tune up your workouts</h5>
                        <h3>The best healt & fitness advice online</h3>
                        <div class="youtube-channel-info">
                            <img src="../assets/img/unnamed.jpg" alt="Channel image" class="logo-channel">
                            <span class="grey-text px-2">ThemeFusion</span>
                        </div>
                        <p class="grey-text">Arcu eu facilisi ut quisque placerat nunc habitant. Magna semper mauris, venenatis, leo integer sit pellentesque.</p>
                        <button class="my-button bg-red">Visit my YouTube channel</button>
                    </div>
                </div>
            </div>
            <div class="youtube-section-bottom">
                <div class="my-container">
                    <div class="description">
                        <h6>Featured playlist</h6>
                        <a href="#" class="black-text">View all videos ></a>
                    </div>
                    <div class="videos-preview pb-5">
                        <div class="row">
                            <div class="col-4">
                                <img src="../assets/img/video2-2x.jpg" alt="Blog 1" class="video-preview">
                                <h5 class="text-center">Thighs & glute workout</h5>
                                <p class="blue-text text-center">Increase your mobility</p>
                            </div>
                            <div class="col-4">
                                <img src="../assets/img/video7-2x.jpg" alt="Blog 2" class="video-preview">
                                <h5 class="text-center">Ultimate cardio workout</h5>
                                <p class="blue-text text-center">By admin | November 26th, 2019 | Gym</p>
                            </div>
                            <div class="col-4">
                                <img src="../assets/img/video9-2x.jpg" alt="Blog 3" class="video-preview">
                                <h5 class="text-center">New juices available now</h5>
                                <p class="blue-text text-center">By admin | November 26th, 2019 | Gym</p>
                            </div>
                </div>
            </div>
        </div>

            </div>
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

.motivational-section{
    background: rgb(29,31,255);
    background: linear-gradient(121deg, rgba(29,31,255,1) 0%, rgba(255,14,45,1) 100%); 
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

.card-img{
    width: 100%;
    height: auto;
}

.my-card{
    position: relative;
}

.text-card{
    position: absolute;
    bottom: 50px;
    left: 50px;
}

.profile-pic{
    border-radius: 50%;
    width: 100px;
    height: 100px;
    padding: 0;
}

.description{
    padding-top: 50px;
    padding-bottom: 30px;
    display: flex;
    justify-content: space-between;
}

.big-video-preview{
    width: 100%;
    height: auto;
}

.video-preview{
    width: 500px;
    height: auto;
}

.logo-channel{
    width: 50px;
}

</style>