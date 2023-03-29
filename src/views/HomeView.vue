<template>
  <v-app id="inspire" :style="{background: $vuetify.theme.themes.dark.background}">
  <SideBar/>
  <SideBarRight/>
  </v-app>
</template>

<script>
  import SideBar from '@/components/SideBar';
  import SideBarRight from '@/components/SideBar';

  export default {
    name: 'home-view',

    components: {
    SideBar,
    SideBarRight
},
  }
</script>
