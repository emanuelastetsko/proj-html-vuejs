<script>

export default {
    name: 'AppMailingListSubscriptionSection',
}

</script>


<template>

    <div class="mailing-list-section">
        <div class="mailing-list-top">
            <div class="my-container">
                <div class="text">
                    <h4 class="red-text py-2">Join our mailing list today</h4>
                    <h2 class="white-text pb-2">Insider offers & flash sales in your inbox every week.</h2>
                    <span class="yellow-text d-block pb-4">!Ondulina!</span>
                    <input type="email" placeholder="Insert your email...*">
                    <button class="bg-blue my-button px-5">Subscribe</button>
                    <p class="grey-text py-4 fs-5">Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet, consectetur adipiscing elit sed porttitor lectus.</p>
                </div>
            </div>
        </div>

        <div class="mailing-list-bottom p-5">
            <div class="my-container">
                <div class="row text-center white-text">

                    <div class="col blue-borders my-card">
                        <span>!Smartwatch!</span>
                        <h5>Team training</h5>
                        <h6 class="yellow-text">Find a partner</h6>
                        <p class="grey-text special-p">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
                        <a href="#">Find a partner ></a>
                    </div>


                    <div class="col blue-borders mx-5 my-card">
                        <span>!Manubrio!</span>
                        <h5>Crossfit workout</h5>
                        <h6 class="yellow-text">Push your limits</h6>
                        <p class="grey-text special-p">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
                        <a href="#">Learn about Crossfit ></a>
                    </div>

                    <div class="col blue-borders my-card">
                        <span>!Corpo!</span>
                        <h5>Weight loss plan</h5>
                        <h6 class="yellow-text">Shed thouse pounds</h6>
                        <p class="grey-text special-p">At laoreet senectus volutpat diam vel sed sed amet pallentesque. Lobortis ut aliquam risus purus. A tellus ut etiam.</p>
                        <a href="#">Schedule a workout ></a>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>


<style lang="scss" scoped>

.mailing-list-top{
    background-image: url(../assets/img/banner1-2x.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    min-height: 700px;
    display: flex;
    align-items: center;
    .text{
        width: 50vw;
    }
}

h2{
    font-size: 2.7em;
}

.my-card{
    min-height: 300px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.special-p{
    padding: 10px 50px;
}


</style>