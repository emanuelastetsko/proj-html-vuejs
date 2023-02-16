<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  data(){
    return {
      linksHeader: [
        {
            name: 'Home',
            url: '#',
        },
        {
            name: 'Services',
            url: '#',
        },
        {
            name: 'About',
            url: '#',
        },
        {
            name: 'Videos',
            url: '#',
        },
        {
            name: 'Blog',
            url: '#',
        },
        {
            name: 'Store',
            url: '#',
        },
      ]   
    }
  }
}

</script>

<template>

  <AppHeader :linksHeaderList="linksHeader"/>

  <AppMain/>

  <AppFooter/>
  
</template>

<style lang="scss">
@use "./styles/main.scss"
</style>
