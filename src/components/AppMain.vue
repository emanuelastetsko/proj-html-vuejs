<script>
import AppJumbotron from './AppJumbotron.vue';
import AppMailingListSubscriptionSectionVue from './AppMailingListSubscriptionSection.vue';
import AppArticlesSection from './AppArticlesSection.vue';
import AppSubscriptionSection from './AppSubscriptionSection.vue'
import AppPartnerSection from './AppPartnerSection.vue';
import AppCrossfitVideosSection from './AppCrossfitVideosSection.vue';


export default {
    name: "AppMain",
    components: { 
        AppJumbotron,
        AppMailingListSubscriptionSectionVue,
        AppArticlesSection,
        AppSubscriptionSection,
        AppPartnerSection,
        AppCrossfitVideosSection, 
    }
}

</script>


<template>

    <main>

        <AppJumbotron/>

        <AppMailingListSubscriptionSectionVue/>
        
        <AppArticlesSection/>

        <AppSubscriptionSection/>

        <AppPartnerSection/>

        <AppCrossfitVideosSection/>

    </main>

</template>


<style lang="scss" scoped>

</style>