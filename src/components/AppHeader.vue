<script>

export default {
    name: 'AppHeader',
}

</script>



<template>

    <header>

        <div class="container my-container">
            <div class="logo">
                <img src="../assets/img/logo-200x34.png" alt="">
            </div>
            <div class="nav-bar">
                <ul>
                    <li>
                        <a href="#" class="grey-text">Home</a>
                    </li>
                    <li>
                        <a href="#" class="grey-text">Services</a>
                    </li>
                    <li>
                        <a href="#" class="grey-text">About</a>
                    </li>
                    <li>
                        <a href="#" class="grey-text">Videos</a>
                    </li>
                    <li>
                        <a href="#" class="grey-text">Blog</a>
                    </li>
                    <li>
                        <a href="#" class="grey-text">Store</a>
                    </li>
                    <li>
                        <button class="bg-blue my-button">Schedule a workout</button>
                    </li>
                    <li>
                        <a href="#">!!Carello!!</a>
                    </li>
                    <li>
                        <a href="#">!!Ricerca!!</a>
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