 <!-- THE HEADER ITEM PAGE-->
<template>
  <div class="itemHeader">

    <!-- ONLY DISPLAY ON MEDIUM AND LARGER DEVICES -->
   <div class="itemHeader1 hidden-sm-and-down">
   <v-layout row wrap justify-space-between class="pa-3">
    <v-flex md6 lg6>
                <v-card class="mx-auto" outlined flat>
                  <v-banner tile color="#ffa500" single-line height="25" width="200" style="margin-top:-10px">
                      <p style="font:normal;font-size:14px;margin-top:-4px;font-weight:bold">Premium Bestseller</p>
                  </v-banner>
                    <v-list-item three-line style="margin-top:-10px">
                        <v-list-item-avatar tile  height="150" width="150" color="grey">
                          <img class="" src="../assets/npa3.png" >
                        </v-list-item-avatar>
                        <v-list-item-content>
                            <div class="items text-capitalize">
                                Continental - Contiecocontact 5
                            </div>
                            <v-list-item-title class="text-h5 mb-1">
                               <v-row>
                                <v-col sm="3" md="3"  lg="3">
                                  <img class="" src="../assets/npa2.png" width="80" height="60">
                                </v-col>
                                <v-col sm="3" md="3" lg="3">
                                  <v-card-texta class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;margin-top:-4px;">205/55 R16 H <br><span>SUV</span>
                                  </v-card-texta>
                                </v-col>
                                <v-col sm="3" md="3" lg="3">
                                 <v-card-texta class="font-italic mt-2" style="text-decoration:none;font-size:12px;font-weight:bold">Stock <span><v-icon color="success">mdi-check-circle</v-icon></span><br><span>Price <v-icon small color="black">mdi-currency-ils</v-icon> 340</span>
                                 </v-card-texta>
                                </v-col>
                                <v-col sm="3" md="3" lg="3">
                                  <v-card-texta class="font-italic mt-2" style="text-decoration:none;font-size:12px;font-weight:bold">Total<span><br><v-icon small color="black">mdi-currency-ils</v-icon>1,360</span>
                                  </v-card-texta>
                                </v-col>
                               </v-row>
                            </v-list-item-title>
                            <v-list-item-subtitle>
                              <v-row>
                                <v-col sm="6" md="6">
                              <div class="mt-3"><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                                </v-col>
                                <v-col sm="6" md="6">
                                  <v-btn rounded class="text-capitalize mt-3" style="font-size:;font-weight:bold;float:right"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                                </v-col>
                              </v-row>
                              
                            </v-list-item-subtitle>
                        </v-list-item-content>  
                    </v-list-item>
                </v-card>
            </v-flex> <v-spacer></v-spacer>
            <v-flex md6 lg6 >
                     <v-card class="mx-auto" outlined flat>
                    <v-banner tile color="#ffa500" single-line height="25" width="200" style="margin-top:-10px">
                      <p style="font:normal;font-size:14px;margin-top:-4px;font-weight:bold">Economy Bestseller</p>
                    </v-banner>
                    <v-list-item three-line style="margin-top:-10px">
                        <v-list-item-avatar tile  height="150" width="150" color="grey">
                          <img class="" src="../assets/npa3.png" >
                        </v-list-item-avatar>
                        <v-list-item-content>
                            <div class="items text-capitalize">
                                Continental - Contiecocontact 5
                            </div>
                            <v-list-item-title class="text-h5 mb-1">
                               <v-row>
                                <v-col sm="3" md="3"  lg="3">
                                  <img class="" src="../assets/npa2.png" width="80" height="60">
                                </v-col>
                           <v-col sm="3" md="3" lg="3">
                                  <v-card-texta class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;margin-top:-4px;">205/55 R16 H <br><span>SUV</span>
                                  </v-card-texta>
                                </v-col>
                                <v-col sm="3" md="3" lg="3">
                                 <v-card-texta class="font-italic mt-2" style="text-decoration:none;font-size:12px;font-weight:bold">Stock <span><v-icon color="success">mdi-check-circle</v-icon></span><br><span>Price <v-icon small color="black">mdi-currency-ils</v-icon> 340</span>
                                 </v-card-texta>
                                </v-col>
                                <v-col sm="3" md="3" lg="3">
                                  <v-card-texta class="font-italic mt-2" style="text-decoration:none;font-size:12px;font-weight:bold">Total<span><br><v-icon small color="black">mdi-currency-ils</v-icon>1,360</span>
                                  </v-card-texta>
                                </v-col>
                               </v-row>
                            </v-list-item-title>
                            <v-list-item-subtitle>
                              <v-row>
                                <v-col sm="6" md="6">
                              <div class="mt-3"><v-btn tile small @click="sub2" v-if="showSubButton2">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input2}}</div></v-btn><v-btn tile small @click="add2">+</v-btn></div>

                                </v-col>
                                <v-col sm="6" md="6">
                                   <v-btn rounded class="text-capitalize mt-3" style="font-size:;font-weight:bold;float:right"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                                </v-col>
                              </v-row>
                              
                            </v-list-item-subtitle>
                        </v-list-item-content>  
                    </v-list-item>
                </v-card>
            </v-flex> 

   </v-layout>
   </div>
  

    <!-- ONLY DISPLAY ON MOBILE DEVICES -->
    <div class="itemHeader2 mx-auto hidden-md-and-up" elevation="8" width="100%" style="margin-top:-20px">
      <v-slide-group v-model="model" class="" active-class="success" show-arrow>
        <v-slide-item >
          <v-card :color="active ? undefined : 'greys lighten-1'" class="ma-2" height="220" width="700" >
            <v-row class="fill-height pa-3"  justify-space-between>
               <v-banner tile color="#ffa500" single-line height="25" width="200" style="margin-top:-10px">
                      <p style="font:normal;font-size:14px;margin-top:-4px;font-weight:bold">Premium Bestseller</p>
                </v-banner>
                 <v-card class="mx-auto" outlined flat height="220" width="700">
                    <v-list-item three-line>
                        <v-list-item-avatar tile  height="150" width="150" color="grey">
                          <img class="" src="../assets/npa3.png" >
                        </v-list-item-avatar>
                        <v-list-item-content>
                            <div class="items text-capitalize">
                                Continental - Contiecocontact 5
                            </div>
                            <v-list-item-title class="text-h5 mb-1">
                               <v-row color="black">
                                <v-col sm="6" md="6">
                                  <img class="" src="../assets/npa2.png" width="80" height="60">
                                </v-col>
                                <v-col sm="6" md="6">
                                  <v-card-texta class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                                  </v-card-texta>
                                </v-col>
                                
                               </v-row>
                            </v-list-item-title>
                             <v-list-item-subtitle>
                              <v-row color="black">
                               <v-col sm="4" md="4">
                                 <v-card-texta class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;color:black">Stock<span><br><v-icon small color="success">mdi-check-circle</v-icon></span>
                                 </v-card-texta>
                                </v-col>
                                <v-col sm="4" md="4">
                                 <v-card-texta  class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;color:black">Price<span><br><v-icon small color="black">mdi-currency-ils</v-icon>340</span>
                                 </v-card-texta>
                                </v-col>
                                <v-col sm="4" md="4">
                                  <v-card-texta class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;color:black">Total<span><br><v-icon small color="black">mdi-currency-ils</v-icon><span style="color:black;font-family:calibri;font-size:14px;font-weight:bold">1,360</span></span>
                                  </v-card-texta>
                                </v-col>
                              </v-row>
                              
                            </v-list-item-subtitle>
                            <v-list-item-subtitle>
                              <v-row>
                                <v-col sm="6" md="6">
                              <div class="mt-3"><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                                </v-col>
                                <v-col sm="6" md="6">
                                   <v-btn rounded class="text-capitalize mt-3" style="font-size:;font-weight:bold;float:right"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px"><span class="text-lowercase"></span></span>
                                  </v-btn>
                                </v-col>
                              </v-row>
                              
                            </v-list-item-subtitle>
                        </v-list-item-content>  
                    </v-list-item>
                </v-card>
            </v-row>
          </v-card>
        </v-slide-item>
        <v-slide-item >
          <v-card :color="active ? undefined : 'greys lighten-1'" class="ma-2" height="220" width="700" >
            <v-row class="fill-height pa-3"  justify-space-between>
               <v-banner tile color="#ffa500" single-line height="25" width="200" style="margin-top:-10px">
                      <p style="font:normal;font-size:14px;margin-top:-4px;font-weight:bold">Economy Bestseller</p>
                </v-banner>
                 <v-card class="mx-auto" outlined flat height="220" width="700">
                    <v-list-item three-line>
                        <v-list-item-avatar tile  height="150" width="150" color="grey">
                          <img class="" src="../assets/npa3.png" >
                        </v-list-item-avatar>
                        <v-list-item-content>
                            <div class="items text-capitalize">
                                Continental - Contiecocontact 5
                            </div>
                            <v-list-item-title class="text-h5 mb-1">
                               <v-row color="black">
                                <v-col sm="6" md="6">
                                  <img class="" src="../assets/npa2.png" width="80" height="60">
                                </v-col>
                                <v-col sm="6" md="6">
                                  <v-card-texta class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                                  </v-card-texta>
                                </v-col>
                                
                               </v-row>
                            </v-list-item-title>
                             <v-list-item-subtitle>
                              <v-row color="black">
                               <v-col sm="4" md="4">
                                 <v-card-texta class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;color:black">Stock<span><br><v-icon small color="success">mdi-check-circle</v-icon></span>
                                 </v-card-texta>
                                </v-col>
                                <v-col sm="4" md="4">
                                 <v-card-texta  class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;color:black">Price<span><br><v-icon small color="black">mdi-currency-ils</v-icon>340</span>
                                 </v-card-texta>
                                </v-col>
                                <v-col sm="4" md="4">
                                  <v-card-texta class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;color:black">Total<span><br><v-icon small color="black">mdi-currency-ils</v-icon><span style="color:black;font-family:calibri;font-size:14px;font-weight:bold">1,360</span></span>
                                  </v-card-texta>
                                </v-col>
                              </v-row>
                              
                            </v-list-item-subtitle>
                            <v-list-item-subtitle>
                              <v-row>
                                <v-col sm="6" md="6">
                              <div class="mt-3"><v-btn tile small @click="sub2" v-if="showSubButton2">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input2}}</div></v-btn><v-btn tile small @click="add2">+</v-btn></div>

                                </v-col>
                                <v-col sm="6" md="6">
                                   <v-btn rounded class="text-capitalize mt-3" style="font-size:;font-weight:bold;float:right"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px"><span class="text-lowercase"></span></span>
                                  </v-btn>
                                </v-col>
                              </v-row>
                              
                            </v-list-item-subtitle>
                        </v-list-item-content>  
                    </v-list-item>
                </v-card>
            </v-row>
          </v-card>
        </v-slide-item>
      </v-slide-group><br>
    </div>

   
            
  </div>
</template>

<script>
export default {
  name: 'ItemHeader',
  data(){
    return{
      input1 : 4,
      input2 : 4,
      showSubButton1 : true,
      showSubButton2 : true
    }
  },
   updated(){
    if(this.input1 < 1){
        this.input1=0;
        this.showSubButton1 = false;
      }
       if(this.input1 == 1){
        this.input1=1;
        this.showSubButton1=true;
      }
       if(this.input2 < 1){
        this.input2=0;
        this.showSubButton2 = false;
      }
       if(this.input2 == 1){
        this.input2=1;
        this.showSubButton2=true;
      }
  },
  methods:{
    add1(){
      const a = this.input1++;
      this.showSubButton1 = true;
    },
    sub1(){
      const a = this.input1--;  
    },
     add2(){
      const a = this.input2++;
      this.showSubButton2 = true;
    },
    sub2(){
      const a = this.input2--;  
    }
  }
 
}

</script>

<style scoped>
    .items{
        color: var(--unnamed-color-000000);
        text-align: left;
        text-decoration: underline;
        font: normal normal bold 24px/34px Calibri;
        letter-spacing: 0px;
        color: #000000;
        opacity: 1;
    }
</style>