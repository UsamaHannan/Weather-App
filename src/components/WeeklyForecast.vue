<template>
    <div>
<div class="box">

</div>

<div class="border1">
    <div class="box1">

</div>
    <h1 class="ma-3 mb-4">Weekly ForeCast</h1>
<v-container >

<v-row >
   
<v-col><p><b class="bold1">Today</b></p></v-col>
<v-col >   <v-img
      class="imag"
      max-height="80"
      max-width="80"
      src="../assets/2.png"
    ></v-img> 
    </v-col>
    <v-col><span><b >Sunny</b></span></v-col>
<v-col class="d-flex justify-end"><p>36/<b class="bold1">22</b></p></v-col>

 
</v-row>

<v-row >
   
    <v-col><p><b class="bold1">Today</b></p></v-col>
   <v-col >   <v-img
         class="imag"
         max-height="80"
         max-width="80"
         src="../assets/2.png"
       ></v-img> 
       </v-col>
       <v-col><span><b>Sunny</b></span></v-col>
   <v-col class="d-flex justify-end"><p>36/<b class="bold1">22</b></p></v-col>
   
    
   </v-row>
   <v-row >
   
    <v-col><p><b class="bold1">Today</b></p></v-col>
   <v-col >   <v-img
         class="imag"
         max-height="80"
         max-width="80"
         src="../assets/3.png"
       ></v-img> 
       </v-col>
       <v-col><span><b>Sunny</b></span></v-col>
   <v-col class="d-flex justify-end"><p>36/<b class="bold1">22</b></p></v-col>
   
    
   </v-row>
   <v-row >
   
    <v-col><p><b class="bold1">Today</b></p></v-col>
   <v-col >   <v-img
         class="imag"
         max-height="80"
         max-width="80"
         src="../assets/1.png"
       ></v-img> 
       </v-col>
       <v-col><span><b>Cloudy</b></span></v-col>
   <v-col class="d-flex justify-end"><p>36/<b class="bold1">22</b></p></v-col>
   
    
   </v-row>
   <v-row >
   
    <v-col><p><b class="bold1">Today</b></p></v-col>
   <v-col >   <v-img
         class="imag"
         max-height="80"
         max-width="80"
         src="../assets/1.png"
       ></v-img> 
       </v-col>
       <v-col><span><b>Cloudy</b></span></v-col>
   <v-col class="d-flex justify-end"><p>36/<b class="bold1">22</b></p></v-col>
   
    
   </v-row>
   <v-row >
   
    <v-col><p><b class="bold1">Today</b></p></v-col>
   <v-col >   <v-img
         class="imag"
         max-height="80"
         max-width="80"
         src="../assets/3.png"
       ></v-img> 
       </v-col>
       <v-col><span><b>Stormy</b></span></v-col>
   <v-col class="d-flex justify-end"><p>36/<b class="bold1">22</b></p></v-col>
   
    
   </v-row>
   <v-row >
   
    <v-col><p><b class="bold1">Today</b></p></v-col>
   <v-col >   <v-img
         class="imag"
         max-height="80"
         max-width="80"
         src="../assets/3.png"
       ></v-img> 
       </v-col>
       <v-col><span><b>Stormy</b></span></v-col>
   <v-col class="d-flex justify-end"><p>36/<b class="bold1">22</b></p></v-col>
   
    
   </v-row>
</v-container>

</div>


    </div>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      
    }),
  }
</script>
<style>
.bold1{
    color: #a09f9f;
}
.box{
    height: 20px;
}
.box1{
    height: 10px;
}
.imag{
    bottom:34%;
   left:45%;
}
.border1{
  margin-left: 8px;
      margin-right: 8px;
      background: #eaecec;
      border-radius: 20px;
      text-decoration: none;
}
</style>