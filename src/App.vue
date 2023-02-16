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
      ], 
      linksFooter: [
        {
          name: '> The best protein shake',
          url: '#',
        },
        {
          name: '> Ultimate cardio workout',
          url: '#',
        },
        {
          name: '> New juices available now',
          url: '#',
        },
        {
          name: '> Tips to find training partners',
          url: '#',
        },
        {
          name: '> 20 best healthy recipes',
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

  <AppFooter :linksFooterList="linksFooter"/>
  
</template>

<style lang="scss">
@use "./styles/main.scss"
</style>
