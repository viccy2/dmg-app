 <!-- THE BODY ITEM PAGE -->
<template>
     <div class="itemBody">
        <!-- DISPLAY ONLY ON LARGER DEVICES -->
        <div class="itemBody1 hidden-md-and-down"><br>
             <v-card  flat height="80" >
                <v-layout row wrap>
                             <v-flex lg2 md2 class="pa-3">
                        <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>
                    </v-flex>
                    <v-flex lg1 md1 class="pa-3">
                       <img class="" src="../assets/npa2.png" width="80" height="60">
                    </v-flex>
                    <v-flex lg2 md2 class="pa-3">
                       <v-card-text class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                    </v-flex>
                    <v-flex lg1 md1 class="pa-3">
                       <v-card-text class="font-italic " style="text-decoration:none;font-size:12px;font-weight:bold;">Stock <span><v-icon color="success" small> mdi-check-circle</v-icon><br><span style="font-size:10px;font-family:calibri;color:black"> </span></span>
                       </v-card-text>
                    </v-flex>
                    <v-flex lg1 md1 class="pa-3">
                        <v-card-text class="font-italic mt-2" style="text-decoration:none;font-size:12px;font-weight:bold">Price<span><v-icon color="black" small style="font-size:7px">mdi-currency-ils</v-icon><span style="font-size:10px"><b>340</b></span></span>
                        </v-card-text>
                    </v-flex>
                   
                    <v-flex lg2 md2 class="pa-3">
                              <div class="mt-3"><v-btn tile small @click="sub3" v-if="showSubButton3">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input3}}</div></v-btn><v-btn tile small @click="add3">+</v-btn></div>
                    </v-flex>
                     <v-flex lg1 md1 class="pa-3">
                        <v-card-text style="text-decoration:none;font-size:11px;font-weight:bold"><span  class="font-italic ">Total </span> <v-icon color="black" small style="font-size:7px">mdi-currency-ils</v-icon><span style="font: normal normal bold 9px Calibri;"><b>1,360</b></span>
                        </v-card-text>
                    </v-flex>
                    <v-flex lg2 md2 class="pa-3">
                        <v-btn rounded class="text-capitalize mt-3" style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                       
                    </v-flex>

                </v-layout>
        
            </v-card><br><br>

            <v-card  flat height="80" >
                <v-layout row wrap>
                              <v-flex lg2 md2 class="pa-3">
                        <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>
                    </v-flex>
                    <v-flex lg1 md1 class="pa-3">
                       <img class="" src="../assets/npa2.png" width="80" height="60">
                    </v-flex>
                    <v-flex lg2 md2 class="pa-3">
                       <v-card-text class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                    </v-flex>
                    <v-flex lg1 md1 class="pa-3">
                       <v-card-text class="font-italic " style="text-decoration:none;font-size:12px;font-weight:bold;">Stock <span><v-icon color="warning" small> mdi-alert-circle</v-icon><br><span style="font-size:10px;font-family:calibri;color:black">8 Tires Left </span></span>
                       </v-card-text>
                    </v-flex>
                    <v-flex lg1 md1 class="pa-3">
                        <v-card-text class="font-italic mt-2" style="text-decoration:none;font-size:12px;font-weight:bold">Price<span><v-icon color="black" small style="font-size:7px">mdi-currency-ils</v-icon><span style="font-size:10px"><b>340</b></span></span>
                        </v-card-text>
                    </v-flex>
                   
                    <v-flex lg2 md2 class="pa-3">
                              <div class="mt-3"><v-btn tile small @click="sub3" v-if="showSubButton3">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input3}}</div></v-btn><v-btn tile small @click="add3">+</v-btn></div>
                    </v-flex>
                     <v-flex lg1 md1 class="pa-3">
                        <v-card-text style="text-decoration:none;font-size:11px;font-weight:bold"><span  class="font-italic ">Total </span> <v-icon color="black" small style="font-size:7px">mdi-currency-ils</v-icon><span style="font: normal normal bold 9px Calibri;"><b>1,360</b></span>
                        </v-card-text>
                    </v-flex>
                    <v-flex lg2 md2 class="pa-3">
                        <v-btn rounded class="text-capitalize mt-3" style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                       
                    </v-flex>

                </v-layout>
        
            </v-card><br><br>

             <v-card  flat height="80" >
                <v-layout row wrap>
                    <v-flex lg2 md2 class="pa-3">
                        <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>
                    </v-flex>
                    <v-flex lg1 md1 class="pa-3">
                       <img class="" src="../assets/npa2.png" width="80" height="60">
                    </v-flex>
                    <v-flex lg2 md2 class="pa-3">
                       <v-card-text class="font-italic" style="text-decoration:none;font-size:12px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                    </v-flex>
                    <v-flex lg1 md1 class="pa-3">
                       <v-card-text class="font-italic " style="text-decoration:none;font-size:12px;font-weight:bold;">Stock <span><v-icon color="red" small> mdi-close-circle</v-icon><br><span style="font-size:8px;font-family:calibri;color:red">Back in 1 week !</span></span>
                       </v-card-text>
                    </v-flex>
                    <v-flex lg1 md1 class="pa-3">
                        <v-card-text class="font-italic mt-2" style="text-decoration:none;font-size:12px;font-weight:bold">Price<span><v-icon color="black" small style="font-size:7px">mdi-currency-ils</v-icon><span style="font-size:10px"><b>340</b></span></span>
                        </v-card-text>
                    </v-flex>
                   
                    <v-flex lg2 md2 class="pa-3">
                              <div class="mt-3"><v-btn tile small @click="sub3" v-if="showSubButton3">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input3}}</div></v-btn><v-btn tile small @click="add3">+</v-btn></div>
                    </v-flex>
                     <v-flex lg1 md1 class="pa-3">
                        <v-card-text style="text-decoration:none;font-size:11px;font-weight:bold"><span  class="font-italic ">Total </span> <v-icon color="black" small style="font-size:7px">mdi-currency-ils</v-icon><span style="font: normal normal bold 9px Calibri;"><b>1,360</b></span>
                        </v-card-text>
                    </v-flex>
                    <v-flex lg2 md2 class="pa-3">
                        <v-btn rounded outlined class="text-capitalize mt-3" style="font-size:;font-weight:bold"  color="#ffa500">
                                      
                                    <v-icon left color="black">
                                         mdi-bell
                                    </v-icon> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                       
                    </v-flex>

                </v-layout>
        
            </v-card>

        </div>

        <!-- DISPLAY ONLY ON MEDIUM DEVICES -->
        <div class="itemBody1 hidden-lg-and-up hidden-sm-and-down"><br>
          <v-layout row wrap>
            <v-flex md6 class="pa-3">
                <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex md6>
                    <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex  md6>
                         <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex md3>
                            <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Stock<span><br><v-icon color="success">mdi-check-circle</v-icon></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex md3>
                         <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red">Save <v-icon color="red" style="font-size:10px">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex md6>
                              <div class=""><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex md6>
                             <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>  
                    </v-layout>
                </v-card>
            </v-flex>
            <v-flex md6 class="pa-3">
                <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex md6>
                    <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex  md6>
                         <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex md3>
                            <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Stock <span><v-icon color="warning">mdi-alert-circle</v-icon></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex md3>
                         <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red">Save <v-icon color="red" style="font-size:10px">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex md6>
                              <div class=""><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex md6>
                             <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>   
                    </v-layout>
                </v-card>
            </v-flex>
            
          </v-layout><br><br>

          <v-layout row wrap>
            <v-flex md6 class="pa-3">
               <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex md6>
                    <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex  md6>
                         <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex md3>
                            <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                       <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Stock <span><v-icon color="red">mdi-close-circle</v-icon><br><span style="color:red;font-size:13px;font-family:calibri">Back in 1 week !</span></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic m" style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex md3>
                         <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red">Save <v-icon color="red" style="font-size:10px">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex md6>
                              <div class=""><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex md6>
                             <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>  
                    </v-layout>
                </v-card>
            </v-flex>
            <v-flex md6 class="pa-3">
                <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex md6>
                    <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex  md6>
                         <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex md3>
                            <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                       <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Stock<span><br><v-icon color="success">mdi-check-circle</v-icon></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex md3>
                         <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red">Save <v-icon color="red" style="font-size:10px">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex md6>
                              <div class="mt-3"><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex md6>
                             <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>   
                    </v-layout>
                </v-card>
            </v-flex>
            
          </v-layout><br><br>

          <v-layout row wrap>
            <v-flex md6 class="pa-3">
              <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex md6>
                    <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex  md6>
                         <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex md3>
                            <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                      <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Stock<span><br><v-icon color="success">mdi-check-circle</v-icon></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex md3>
                         <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red">Save <v-icon color="red" style="font-size:10px">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex md6>
                              <div class="mt-3"><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex md6>
                             <v-btn rounded class="text-capitalize" style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>   
                    </v-layout>
                </v-card>
            </v-flex>
            <v-flex md6 class="pa-3">
               <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex md6>
                    <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex  md6>
                         <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex md3>
                            <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Stock<span><br><v-icon color="success">mdi-check-circle</v-icon></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex md3>
                         <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red">Save <v-icon color="red" style="font-size:10px">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex md6>
                              <div class="mt-3"><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex md6>
                             <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>   
                    </v-layout>
                </v-card>
            </v-flex>
            
          </v-layout><br><br>

          <v-layout row wrap>
            <v-flex md6 class="pa-3">
              <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex md6>
                    <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex  md6>
                         <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex md3>
                            <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                       <v-flex md3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Stock<span><br><v-icon color="success">mdi-check-circle</v-icon></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex md3>
                         <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red">Save <v-icon color="red" style="font-size:10px">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex md6>
                              <div class=""><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex md6>
                             <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>  
                    </v-layout>
                </v-card>
            </v-flex>
            <v-flex md6 class="pa-3">
               <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex md6>
                    <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex  md6>
                         <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex md3>
                            <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                       <v-flex md3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Stock<span><br><v-icon color="success">mdi-check-circle</v-icon></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex md3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex md3>
                         <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red">Save <v-icon color="red" style="font-size:10px">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex md6>
                              <div class=""><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex md6>
                             <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>   
                    </v-layout>
                </v-card>
            </v-flex>
            
          </v-layout>
            
        </div>

        <!-- DISPLAY ON SMALL DEVICES -->
    <div class="itemBody3 hidden-md-and-up">
         <v-layout row wrap>
            <v-flex  class="pa-3">
                <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex xs6 sm6>
                     <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex xs6 sm6>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex xs3 sm3>
                        <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                        <v-flex xs3 sm3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Stock<span><br><v-icon color="success">mdi-check-circle</v-icon></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex xs3 sm3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:13px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex xs3 sm3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red;font-size:12px;font-family:calibri">Save <v-icon style="font-size:8px;color:red">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex xs6 sm6>
                              <div class=""><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex xs6 sm6>
                          <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>  
                    </v-layout>
                </v-card>
            </v-flex>
        </v-layout><br><br>
        <v-layout row wrap>
            <v-flex  class="pa-3">
                 <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex xs6 sm6>
                     <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex xs6 sm6>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex xs3 sm3>
                        <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                       <v-flex xs3 sm3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Stock <span><v-icon color="warning">mdi-alert-circle</v-icon><br><span style="color:black;font-size:12px;font-family:calibri">8 Tires Left </span></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex xs3 sm3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:13px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex xs3 sm3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red;font-size:12px;font-family:calibri">Save <v-icon style="font-size:8px;color:red">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex xs6 sm6>
                              <div class=""><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex>
                        <v-flex xs6 sm6>
                          <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>   
                    </v-layout>
                </v-card>
            </v-flex>
        </v-layout><br><br>

        <v-layout row wrap>
            <v-flex  class="pa-3">
                <v-card flat height="">
                    <v-layout row wrap class="pa-3">
                        <v-flex xs6 sm6>
                     <v-card-title style="font: normal normal bold 15px Calibri;text-decoration: underline;margin-top:-6px;">Continental <br><span>PremiumContact™ 6</span></v-card-title>

                        </v-flex>
                        <v-flex xs6 sm6>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold;margin-top:-4px;">195/55 R15 85V <br><span>SUV</span>
                       </v-card-text>
                        </v-flex><br><br>
                        <v-flex xs3 sm3>
                        <img class="" src="../assets/npa2.png" width="80" height="60">
                        </v-flex>
                        <v-flex xs3 sm3>
                        <v-card-text class="font-italic " style="text-decoration:none;font-size:14px;font-weight:bold">Stock<span><v-icon color="red">mdi-close-circle</v-icon><br><span style="color:red;font-size:12px;font-family:calibri">Back in 1 week !</span></span>
                        </v-card-text>
                        </v-flex>
                        <v-flex xs3 sm3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Price<span><br><v-icon style="font-size:13px;color:black">mdi-currency-ils</v-icon><span>340</span></span>
                        </v-card-text>
                        </v-flex> 
                        <v-flex xs3 sm3>
                        <v-card-text class="font-italic" style="text-decoration:none;font-size:14px;font-weight:bold">Total <span><v-icon style="font-size:10px;color:black">mdi-currency-ils</v-icon><span>2,312</span><br><span style="color:red;font-size:12px;font-family:calibri">Save <v-icon style="font-size:8px;color:red">mdi-currency-ils</v-icon>408!</span></span>
                        </v-card-text>
                        </v-flex><br><br>
                         <v-flex xs6 sm6>
                              <div class=""><v-btn tile small @click="sub1" v-if="showSubButton1">-</v-btn><v-btn tile small disabled><div style="color:black" value="4" >{{input1}}</div></v-btn><v-btn tile small @click="add1">+</v-btn></div>

                        </v-flex> 
                        <v-flex xs6 sm6>
                           <v-btn rounded class="text-capitalize " style="font-size:;font-weight:bold"  color="#ffa500">
                                      <v-badge  color="black" icon="mdi-plus" overlap style="margin-top:5px">
                                    <v-icon left>
                                         mdi-cart
                                    </v-icon></v-badge> <span style="margin-left:10px">Add <span class="text-lowercase">to</span> Cart</span>
                                  </v-btn>
                        </v-flex>  
                    </v-layout>
                </v-card>
            </v-flex>
        </v-layout>

    </div><br>

        
        

     <!-- THE LOAD MORE BUTTON   -->
     <v-btn
            class="text-capitalize btn1"
            outlined
            color="black"
            width="100%"
            rounded
            style="font: normal normal bold 18px/27px Calibri;"
    >
        Load More Results
    </v-btn>
    </div>
</template>

    
<script>
export default {
  name: 'ItemBody',
  data(){
    return{
      input1 : 8,
      input2 : 8,
      input3 : 4,
      showSubButton1 : true,
      showSubButton2 : true,
      showSubButton3 : true
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
       if(this.input3 < 1){
        this.input3=0;
        this.showSubButton3 = false;
      }
       if(this.input3 == 1){
        this.input3=1;
        this.showSubButton3=true;
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
    },
    add3(){
      const a = this.input3++;
      this.showSubButton3 = true;
    },
    sub3(){
      const a = this.input3--;  
    }
  }

}
</script>
<style scoped>
    p{
         text-align: left;
         text-decoration: underline;
         font: normal normal bold 16px/24px Calibri;
         letter-spacing: 0px;
         color: #000000;
         opacity: 1;
    }
</style>