<template>
    <div>
      <div class="box1">

</div>
        <div class="search-box ma-2">
     <input class="search-txt" type="text" name="" placeholder="Search for cities">
     <button class="search-btn">
        <i class="fas fa-search"></i>
     </button>

</div>

<div>
    <v-card
    class="mx-auto"
    height="250px"
  >
  <v-container>
  <v-row class="m-1" no-gutters>
      <v-col class="mt-5" >
      <h2 class="head">Madrid</h2>
      <p><small>chance of rain:0%</small></p><br>

      <h1 class="head1">31°</h1>
        
      </v-col>
   
      <v-col class="d-flex justify-end">
        <v-img
  
  max-height="250"
  max-width="250"
  src="../assets/sun.png"
></v-img>
       
      </v-col>
    </v-row>
</v-container>
  </v-card>
</div>
<div class="border1 mt-4 pb-3">
<v-container>
   <p class="text-h6 text--primary">
        TODAY'S FORECAST
      </p>
   

   <v-row  >
    <v-col >
        <v-card >
        <h4 class="ml-3 mt-2">
        6:00 AM
        </h4>
      <v-img
      class="ml-4"
  max-height="50"
  max-width="50"
  src="../assets/1.png"
></v-img>
      <h2 class="ml-6">25°</h2>
    </v-card>
    </v-col>
    <v-col>
      <v-card >
        <h4 class="ml-3 mt-2">
        6:00 AM
        </h4>
      <v-img
      class="ml-4"
  max-height="50"
  max-width="50"
  src="../assets/1.png"
></v-img>
      <h2 class="ml-6">25°</h2>
    </v-card>
    </v-col>
    <v-col>
      <v-card >
        <h4 class="ml-3 mt-2">
        6:00 AM
        </h4>
      <v-img
      class="ml-4"
  max-height="50"
  max-width="50"
  src="../assets/2.png"
></v-img>
      <h2 class="ml-6">25°</h2>
    </v-card>
    </v-col>
    <v-col>
      <v-card >
        <h4 class="ml-3 mt-2">
        6:00 AM
        </h4>
      <v-img
      class="ml-4"
  max-height="50"
  max-width="50"
  src="../assets/2.png"
></v-img>
      <h2 class="ml-6">25°</h2>
    </v-card>
    </v-col>
    <v-col>
      <v-card >
        <h4 class="ml-3 mt-2">
        6:00 AM
        </h4>
      <v-img
      class="ml-4"
  max-height="50"
  max-width="50"
  src="../assets/2.png"
></v-img>
      <h2 class="ml-6">25°</h2>
    </v-card>
    </v-col>
    <v-col>
      <v-card >
        <h4 class="ml-3 mt-2">
        6:00 AM
        </h4>
      <v-img
      class="ml-4"
  max-height="50"
  max-width="50"
  src="../assets/3.png"
></v-img>
      <h2 class="ml-6">25°</h2>
    </v-card>
    </v-col>
   </v-row>

</v-container>
</div>


<div class="border1 mt-4 ">
  <v-container>

<v-row>
  <v-col>
<h3 class="ma-2">AIR CONDITIONS</h3>
  </v-col>

  <v-col  class="d-flex justify-end">
    <v-btn
      depressed
   
     class="ma-2 hammer"
    >
      See more
    </v-btn>
  </v-col>
</v-row>


<div>
      <v-row class="m-1">
        <v-col>
          <v-card class="d-flex justify-start mb-6">
            <v-list-item>
              <v-list-item-avatar>
                <v-icon> mdi mdi-thermometer </v-icon>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title> <h4>Real Feel</h4></v-list-item-title>

                <v-list-item-subtitle
                  ><h2>30°</h2></v-list-item-subtitle
                >
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
        <v-col>
          <v-card>
            <v-list-item>
              <v-list-item-avatar>
                <v-icon> mdi mdi-weather-windy </v-icon>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title> <h4>Wind</h4></v-list-item-title>

                <v-list-item-subtitle
                  ><h2>0.2 km/h</h2></v-list-item-subtitle
                >
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
      </v-row>
    </div>

    <div>
      <v-row class="m-1">
        <v-col>
          <v-card class="d-flex justify-start mb-6">
            <v-list-item>
              <v-list-item-avatar>
                <v-icon> mdi mdi-water</v-icon>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title> <h4>Chance of rain</h4></v-list-item-title>

                <v-list-item-subtitle
                  ><h2>0%</h2></v-list-item-subtitle
                >
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
        <v-col>
          <v-card>
            <v-list-item>
              <v-list-item-avatar>
                <v-icon> mdi mdi-sun-wireless</v-icon>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title> <h4>UV Index</h4></v-list-item-title>

                <v-list-item-subtitle
                  ><h2>3</h2></v-list-item-subtitle
                >
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
      </v-row>
    </div>


  </v-container>
</div>
<div class="box2">

</div>
    </div>
</template>
<script>
  export default {
    name: 'ForeCast',

    data: () => ({
      
    }),
  }
</script>

<style>
.hammer{
  background-color: #006dad !important;
  color: whitesmoke !important;
}
.border1{
  margin-left: 8px;
      margin-right: 8px;
      background: #eaecec;
      border-radius: 20px;
      text-decoration: none;
}
.head{
  font-size: 40px;
}
.head1{
  font-size:50px;
}
.box1{
  height: 5px;
}
.search-box
{


 
  background : #eaecec;
  height : 40px;
  border-radius : 40px;

}
.search-btn
{
  color : whitesmoke;
  float : right;
  width : 40px;
  height : 40px;
  border-radius: 50%;
  background : #006dad;
  display:flex;
  justify-content: center;
  align-items: center;
  text-decoration: none;
  transition:0.4s;
}
.search-txt
{
  border:none;
  background:none;
  outline:none;
  float:left;
  padding:0;
  color: black;
  font-size:16px;
  transition : 0.4s;
  line-height: 40px;
  width : 0px;
}
.search-box:hover > .search-txt
{
  width: 240px;
  padding: 0 6px;
}
.search-box:hover > .search-btn
{
 background:white;
 color: #006dad;
}
.box2{
  height: 20px;
}
</style>