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
                        <a :href="link.url">{{ link.name }}</a>
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