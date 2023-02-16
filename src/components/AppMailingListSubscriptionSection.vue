<script>

export default {
    name: 'AppMailingListSubscriptionSection',
}

</script>


<template>

    <div class="mailing-list-section">
        <div class="mailing-list-top">
            <div class="my-container">
                <div class="text fs-4">
                    <h4 class="red-text py-2">Join our mailing list today</h4>
                    <h2 class="white-text pb-2">Insider offers & flash sales in your inbox every week.</h2>
                    <span class="yellow-text d-block pb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-three-dots" viewBox="0 0 16 16">
                            <path d="M3 9.5a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zm5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zm5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3z"/>
                        </svg>
                    </span>
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
                        <span>
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-smartwatch" viewBox="0 0 16 16">
                                <path d="M9 5a.5.5 0 0 0-1 0v3H6a.5.5 0 0 0 0 1h2.5a.5.5 0 0 0 .5-.5V5z"/>
                                <path d="M4 1.667v.383A2.5 2.5 0 0 0 2 4.5v7a2.5 2.5 0 0 0 2 2.45v.383C4 15.253 4.746 16 5.667 16h4.666c.92 0 1.667-.746 1.667-1.667v-.383a2.5 2.5 0 0 0 2-2.45V8h.5a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-.5-.5H14v-.5a2.5 2.5 0 0 0-2-2.45v-.383C12 .747 11.254 0 10.333 0H5.667C4.747 0 4 .746 4 1.667zM4.5 3h7A1.5 1.5 0 0 1 13 4.5v7a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 11.5v-7A1.5 1.5 0 0 1 4.5 3z"/>
                            </svg>
                        </span>
                        <h5>Team training</h5>
                        <h6 class="yellow-text">Find a partner</h6>
                        <p class="grey-text special-p">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
                        <a href="#">Find a partner ></a>
                    </div>


                    <div class="col blue-borders mx-5 my-card">
                        <span>
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-lungs-fill" viewBox="0 0 16 16">
                                <path d="M8 1a.5.5 0 0 1 .5.5v5.243L9 7.1V4.72C9 3.77 9.77 3 10.72 3c.524 0 1.023.27 1.443.592.431.332.847.773 1.216 1.229.736.908 1.347 1.946 1.58 2.48.176.405.393 1.16.556 2.011.165.857.283 1.857.24 2.759-.04.867-.232 1.79-.837 2.33-.67.6-1.622.556-2.741-.004l-1.795-.897A2.5 2.5 0 0 1 9 11.264V8.329l-1-.715-1 .715V7.214c-.1 0-.202.03-.29.093l-2.5 1.786a.5.5 0 1 0 .58.814L7 8.329v2.935A2.5 2.5 0 0 1 5.618 13.5l-1.795.897c-1.12.56-2.07.603-2.741.004-.605-.54-.798-1.463-.838-2.33-.042-.902.076-1.902.24-2.759.164-.852.38-1.606.558-2.012.232-.533.843-1.571 1.579-2.479.37-.456.785-.897 1.216-1.229C4.257 3.27 4.756 3 5.28 3 6.23 3 7 3.77 7 4.72V7.1l.5-.357V1.5A.5.5 0 0 1 8 1Zm3.21 8.907a.5.5 0 1 0 .58-.814l-2.5-1.786A.498.498 0 0 0 9 7.214V8.33l2.21 1.578Z"/>
                            </svg>
                        </span>
                        <h5>Crossfit workout</h5>
                        <h6 class="yellow-text">Push your limits</h6>
                        <p class="grey-text special-p">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
                        <a href="#">Learn about Crossfit ></a>
                    </div>

                    <div class="col blue-borders my-card">
                        <span>
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-graph-down-arrow" viewBox="0 0 16 16">
                                <path fill-rule="evenodd" d="M0 0h1v15h15v1H0V0Zm10 11.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-4a.5.5 0 0 0-1 0v2.6l-3.613-4.417a.5.5 0 0 0-.74-.037L7.06 8.233 3.404 3.206a.5.5 0 0 0-.808.588l4 5.5a.5.5 0 0 0 .758.06l2.609-2.61L13.445 11H10.5a.5.5 0 0 0-.5.5Z"/>
                            </svg>
                        </span>
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
    background-image: linear-gradient(90deg, rgb(4, 5, 15) 39%, rgba(6,6,7,0) 100%), url(../assets/img/banner1-2x.jpg);
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