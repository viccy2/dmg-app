<template>
<div class="home grey lighten-2"  >
    <!-- THE NAVBAR COMPONENT -->
    <Navbar/>
    <v-container fluid mt-4>
      <h3>Recommended Products</h3>
      <!-- DISPLAY ON LARGER DEVICES -->
      <div class="home1 hidden-sm-and-down">
      <v-layout row wrap justify-space-between>
        <v-flex xs7 sm5 md6 style="margin-top:13px"><span class="pa-3 font-italic" style="font-size:14px;font-weight:bold">Selected Filters : </span>
          <v-btn flat  outlined  class="items ma-2 black--text text-capitalize font-italic">
            Continental 
            <v-icon right dark>
               mdi-close-circle-outline
            </v-icon>
          </v-btn>
        </v-flex>
        <v-flex xs5 sm7 md6><span class="pa-3 font-italic" style="float:right;font-size:14px;font-weight:bold">Sort by :
          <v-btn outlined class="items ma-2 black--text text-capitalize font-italic" >
            Popularity
            <v-icon right dark>
              mdi-chevron-down
            </v-icon>
          </v-btn></span>
       </v-flex>
      </v-layout>

      </div>

      <v-divider style="background:black"></v-divider><br>

    <!-- THE ITEMHEADER COMPONENT -->
    <ItemHeader/>
    
    <!-- THE ITEMBODY COMPONENT -->
    <ItemBody/>
     
    
     </v-container>
</div>
</template>
  
<script>
import Navbar from '../components/Navbar'
import ItemHeader from '../components/ItemHeader'
import ItemBody from '../components/ItemBody'
  export default {
    name: 'Home',
    components: {
      ItemBody,
      ItemHeader,
      Navbar

    },
  }
</script>
<style scoped>
  p{
    text-align: left;
    font: normal normal bold 16px/23px italic;
    letter-spacing: 0px;
    color: #363636;
    opacity: 1;
  }
 .items{
    text-align: left;
    font: italic;
    font-weight : bold; 
    letter-spacing: 0px;
    color: black;
    opacity: 1;
    font-size:11px;
    border-color:black;
    border-radius: 40px;
 }
 
</style>