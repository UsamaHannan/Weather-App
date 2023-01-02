<template>
  <v-app>
    <v-container fluid class="grey lighten-5">
    <v-row class="m-1" no-gutters>
      <v-col md="1">
        <v-card><SideBar/></v-card>
        
      </v-col>
      <v-col md="6" >
        <v-card> <ForeCast/></v-card>
       
      </v-col>
      <v-col md="5">
        <v-card class="ma-6"> <WeeklyForecast/></v-card>
       
      </v-col>
    </v-row>
  </v-container>
  
  </v-app>
</template>

<script>
import SideBar from './components/SideBar';
import ForeCast from './components/ForeCast';
import WeeklyForecast from './components/WeeklyForecast';


export default {
  name: 'App',

  components: {
    WeeklyForecast,
    ForeCast,
    SideBar,
  },

  data: () => ({
    //
  }),
};
</script>
