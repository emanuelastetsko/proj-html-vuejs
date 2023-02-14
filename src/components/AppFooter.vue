<script>

export default {
    name: 'AppFooter',
}

</script>


<template>

    <footer>

        <div class="container my-container footer-top py-5">
            <div class="row">
                <div class="col-4 text-center">
                    <img src="../assets/img/logo-mobile.png" alt="Logo">
                    <p class="py-3 grey-text">Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. Pellentesque consectetur amet purus ultrices mauris.</p>
                    <span class="red-text">
                        <span>Facebook</span>
                        <span>Twitter</span>
                        <span>Youtube</span>
                        <span>Instagram</span>
                        <span>LinkedIn</span>
                    </span>
                </div>
                <div class="col-4 text-center">
                    <ul>
                        <li>
                            <h6 class="py-2">RECENT POSTS</h6>
                        </li>
                        <li class="pb-2">
                            <a href="#">> The best protein shake</a>
                        </li>
                        <li class="pb-2">
                            <a href="#">> Ultimate cardio workout</a>
                        </li>
                        <li class="pb-2">
                            <a href="#">> New juices availoable now</a>
                        </li>
                        <li class="pb-2">
                            <a href="#">> Tips to find training partners</a>
                        </li>
                        <li class="pb-2">
                            <a href="#">> 20 best healty recipes</a>
                        </li>
                    </ul>
                </div>
                <div class="col-4 text-center">
                    <h6 class="py-2">CONTACT INFORMATIONS</h6>
                    <span class="grey-text">4746 Tipple Road Michigan 48449</span>
                    <div class="contacts py-2">
                        <span>Mobile: 1.800.000.0000</span>
                        <br>
                        <span>Email: info@your-company.com</span>
                    </div>
                </div>
            </div>
        </div>

        <hr>

        <div class="footer-bottom">
            <span class="grey-text">
                @Copyright 2012 - 2020 | Avada theme by 
                <span class="white-text">ThemeFusion</span> 
                | All rights reserved | Powered by 
                <span class="white-text">WordPress</span> 
            </span>
        </div>

    </footer>

</template>


<style lang="scss" scoped>

.footer-top{
    color: white;
}

.footer-bottom{
    min-height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;
}

</style>