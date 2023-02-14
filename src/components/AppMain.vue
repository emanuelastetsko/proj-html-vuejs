<script>
import AppJumbotron from './AppJumbotron.vue';
import AppCrossfitVideosSection from './AppCrossfitVideosSection.vue';
import AppPartnerSection from './AppPartnerSection.vue'

export default {
    name: "AppMain",
    components: { 
        AppJumbotron,
        AppCrossfitVideosSection, 
        AppPartnerSection
    }
}

</script>


<template>

    <main>

        <AppJumbotron/>

        <AppPartnerSection/>

        <AppCrossfitVideosSection/>

    </main>

</template>


<style lang="scss" scoped>

</style>