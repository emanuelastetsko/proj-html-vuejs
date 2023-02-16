<script>
export default {
    name: 'AppHeader',
    props: {
        linksHeaderList: {
            type: Array,
            default: []
        }
    }
}

</script>



<template>

    <header>

        <div class="my-container">
            <div class="logo">
                <img src="../assets/img/logo-200x34.png" alt="Logo">
            </div>
            <div class="nav-bar">
                <ul>
                    <li v-for="link in linksHeaderList">
                        <a :href="link.url" class="grey-text">{{ link.name }}</a>
                    </li>
                    <li>
                        <button class="bg-blue my-button">Schedule a workout</button>
                    </li>
                    <li>
                        <a href="#" class="grey-text">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-cart-fill" viewBox="0 0 16 16">
                                <path d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .491.592l-1.5 8A.5.5 0 0 1 13 12H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5zM5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2zm7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2z"/>
                            </svg>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="grey-text">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                                <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                            </svg>
                        </a>
                    </li>
                </ul>
            </div>
        </div>

    </header>

</template>


<style lang="scss" scoped>

header{
    min-height: 80px;
    display: flex;
    justify-content: center;
}

.my-container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    .nav-bar ul{
        display: flex;
        align-items: center;

        li{
            padding: 0 15px;
            font-size: 1.2em;
        }
    }
}





</style>