<template>
  <div class="bar">
    <!-- ONLY DISPLAY ON LARGER DEVICES -->
    <div class="bar1 hidden-md-and-down">
      <v-app-bar fixed >
      <v-app-bar-nav-icon><v-btn icon>
        <v-icon>mdi-tune</v-icon>
        </v-btn></v-app-bar-nav-icon>
      <v-toolbar-title><img src="../assets/NoPath.png" width="100%"></v-toolbar-title>
      <v-spacer></v-spacer>

        <!-- THE SEARCH ICON -->
      <div class="search-box">
        <input class="search-txt" type="text" name="" placeholder="Search..." >
        <span class="search-btn" href="#">
        <v-icon color='black' >mdi-magnify</v-icon>
        </span>
       </div>

      <v-spacer></v-spacer>
      <!-- THE ICONS -->

      <div class="d-flex flex-column align-center">
        <v-btn icon height="30" style="margin-top:20px">
          <v-icon>mdi-account</v-icon>
        </v-btn>
        <p class="font-italic">Account</p>
      </div>
      <div class="d-flex flex-column align-center">
        <v-btn icon height="30" style="margin-top:20px">
          <v-icon>mdi-file-document</v-icon>
        </v-btn>
        <p class="font-italic">Orders</p>
      </div>
      <div class="d-flex flex-column align-center">
        <v-btn icon height="30" style="margin-top:20px">
           <v-badge
            dot
            bordered
            color="#ffa500"
            overlap
      >
          <v-icon>mdi-cart</v-icon></v-badge>
        </v-btn>
        <p class="font-italic">Cart</p>
      </div>
     
      </v-app-bar>
    </div>
 <!-- ONLY DISPLAY ON MEDIUM DEVICES -->
 <div class="bar3 hidden-lg-and-up">
      <v-app-bar fixed >
      <v-app-bar-nav-icon><v-btn icon>
        <v-icon>mdi-tune</v-icon>
        </v-btn></v-app-bar-nav-icon>
        <v-toolbar-title><img src="../assets/npa.png" width="100%" style="height:30px"></v-toolbar-title>
      <v-spacer></v-spacer>

        <!-- THE SEARCH ICON -->
      <div class="search-box">
        <input class="search-txt" type="text" name="" placeholder="Search..." >
        <span class="search-btn" href="#">
        <v-icon color='black' >mdi-magnify</v-icon>
        </span>
       </div>

      <v-spacer></v-spacer>
      <!-- THE ICONS -->

      <div class="d-flex flex-column align-center">
        <v-btn icon height="30" style="margin-top:20px">
          <v-icon>mdi-account</v-icon>
        </v-btn>
        <p class="font-italic">Account</p>
      </div>
      <div class="d-flex flex-column align-center">
        <v-btn icon height="30" style="margin-top:20px">
          <v-icon>mdi-file-document</v-icon>
        </v-btn>
        <p class="font-italic">Orders</p>
      </div>
      <div class="d-flex flex-column align-center">
        <v-btn icon height="30" style="margin-top:20px">
           <v-badge
            dot
            bordered
            color="#ffa500"
            overlap
      >
          <v-icon>mdi-cart</v-icon></v-badge>
        </v-btn>
        <p class="font-italic">Cart</p>
      </div>
     
      </v-app-bar>
    </div>


  <!-- ONLY DISPLAY ON SMALL DEVICES -->
    <div class="bar2 hidden-md-and-up">
          <v-app-bar fixed >
          <v-app-bar-nav-icon >
            <v-btn icon>
              <v-icon class="container ma-3">mdi-tune</v-icon>
            </v-btn>
          </v-app-bar-nav-icon><v-spacer></v-spacer>
          <v-toolbar-title><img src="../assets/npa.png" width="100%" style="height:30px"></v-toolbar-title>
          <v-spacer></v-spacer><v-spacer></v-spacer><v-spacer></v-spacer><v-spacer></v-spacer><v-spacer></v-spacer><v-spacer></v-spacer>
        <div class="text-center">
          <v-btn class="mx-2" fab dark small color="#ffa500">
            <v-icon color="black"> mdi-magnify</v-icon>
          </v-btn>
        </div>
        <v-spacer></v-spacer>

        <div class="d-flex flex-column align-center">
          <v-btn icon height="30" style="margin-top:20px">
            <v-icon>mdi-account</v-icon>
          </v-btn>
          <p class="font-italic">Account</p>
        </div>

        <div class="d-flex flex-column align-center">
          <v-btn icon height="30" style="margin-top:20px">
           <v-icon>mdi-file-document</v-icon>
          </v-btn>
          <p class="font-italic">Orders</p>
        </div>

        <div class="d-flex flex-column align-center">
         <v-btn icon height="30" style="margin-top:20px">
           <v-badge
              bordered
              color="#ffa500"
              overlap dot
      >
          <v-icon>mdi-cart</v-icon></v-badge>
        </v-btn>
          <p class="font-italic">Cart</p>
        </div>
    </v-app-bar>
    </div><br><br><br>

  </div>
</template>

<script>
export default {
    
}
</script>
<style scoped>
  p{
      font-family: inherit;
      font-size:10px;
      letter-spacing: 0px;
      color: #9C9D9D;
      opacity: 1;margin-top:-5px;
  }
  .search-box{
    position : absolute;
    top : 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-family: italic;
    height: 30px;
    border-radius:40px;
    padding: 2px;
    padding-right:0px;
    width:45%;
    border: 1px solid grey;
    
  
  }
  .search-btn{
    color: #ffa500;
    float:right;
    width:30px;
    height:30px;
    border-radius:50%;
    background: #ffa500;
    display: flex;
    justify-content: center;
    align-items:center ;
    margin-top:-27px;
    cursor: pointer;
  }
  .search-txt{

    border: red;
    background: none;
    outline: none;
    font-family:italic;
    padding-right:-10;
    color:grey;
    font-size: 14px;
    transition:0.4s;
    line-height:-10px;
    width: 100%;
    margin-left:50px;

  }
</style>