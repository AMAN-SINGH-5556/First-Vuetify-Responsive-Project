 



 <template>
  <v-form v-model="valid">
       <v-app-bar>
            <v-btn icon>
                <v-icon>mdi-chevron-left</v-icon>
            </v-btn>
            <v-flex>
                <v-toolbar-title class="justify-center" align="center" >Account</v-toolbar-title>
            </v-flex>
        </v-app-bar>
    <v-container class="text-center">

      <v-row align="center" justify="center"> 
          <v-col cols="12">
            <v-avatar>
              <v-btn fab>
                <v-img fab :src="require('../assets/logo.svg')" alt="John" />
              </v-btn>
            </v-avatar>
            <h4>Parth Admin</h4>
          </v-col>
          <v-col cols="4">
            <v-btn small fab class="elevation-4">
              <v-icon>mdi-heart</v-icon>
            </v-btn>
            <h5 class="mt-3">My Wish List</h5>
          </v-col>
          <v-col cols="4">
            <v-btn small fab class="elevation-4">
              <v-icon>mdi-earth</v-icon>
            </v-btn>
            <h5 class="mt-3">Language</h5>
          </v-col>
          <v-col cols="4">
            <v-btn small fab class="elevation-4">
              <v-icon>mdi-account-circle-outline</v-icon>
            </v-btn>
            <h5 class="mt-3">My Profile</h5>
          </v-col>
          <v-col cols="4">
            <v-btn small fab class="elevation-4">
              <v-icon>mdi-bell</v-icon>
            </v-btn>
            <h5 class="mt-3">Notifications</h5>
          </v-col>
          <v-col cols="4">
            <v-btn small fab class="elevation-4">
              <v-icon>mdi-map-marker</v-icon>
            </v-btn>
            <h5 class="mt-3">My Addresses</h5>
          </v-col>
          <v-col cols="4">
            <v-btn small fab class="elevation-4">
              <v-icon>mdi-cart</v-icon>
            </v-btn>
            <h5 class="mt-3">My Orders</h5>
          </v-col>
          <v-col cols="4">
            <v-btn small fab class="elevation-4">
              <v-icon>mdi-help</v-icon>
            </v-btn>
            <h5 class="mt-3">Help</h5>
          </v-col>
        </v-row>





<!-- 

      <v-row>
        <v-col cols="12" md="12">
            <h2>DELIVERY INFORMATION</h2>
            <p class="font-weight-light caption">Fill all the details for delivery location</p>
        </v-col>
        
        <v-col
          cols="12"
          md="12"
        >
          <v-text-field
            v-model="fullname"
            :rules="nameRules"
            label="Full name"
            placeholder="Full Name"
            required
          ></v-text-field>
        </v-col>

        <v-col
          cols="6"
          md="6"
        >
          <v-text-field
            v-model="flatno"
            :rules="nameRules"
            label="Flat No."
            placeholder="Flat Number"
            required
          ></v-text-field>
        </v-col>

        <v-col
          cols="6"
          md="6"
        >
          <v-text-field
            v-model="blockno"
            :rules="nameRules"
            label="Block No."
            placeholder="Block Number"
            required
          ></v-text-field>
        </v-col>

        <v-col
          cols="12"
          md="12"
        >
          <v-text-field
            v-model="address"
            :rules="nameRules"
            label="Address"
             append-icon="mdi-crosshairs-gps"
            placeholder="123,abc street"
            required
          ></v-text-field>
        </v-col>

        <v-col
          cols="12"
          md="12"
        >
          <v-text-field
            v-model="pincode"
            :rules="nameRules"
            label="Pincode"
            placeholder="eg. 000000"
            required
          ></v-text-field>
        </v-col>

        <v-col
          cols="6"
          md="6"
        >
          <v-text-field
            v-model="city"
            :rules="nameRules"
            label="City"
            placeholder="Ahmedabad"
            required
          ></v-text-field>
        </v-col>

        <v-col
          cols="6"
          md="6"
        >
          <v-text-field
            v-model="state"
            :rules="nameRules"
            label="State"
            placeholder="Gujarat"
            required
          ></v-text-field>
        </v-col>
      </v-row>
    
      <v-flex class="justify-center">
        <div class="text-center">
            <v-btn
            depressed
            color="#5C3F69"
            large
            >
            Submit
            </v-btn>
            <v-btn 
            depressed
            text
            outlined
            large
            >
            Cancel
            </v-btn>
        </div>
      </v-flex> -->
   
    </v-container>


  <template>

 







   
   
   
     <v-row justify="space-around"><v-col cols="12"
        sm="6"
        md="10" ><h2>Last Order</h2></v-col></v-row>
     
    <v-row align="center" justify="center" >
      
    <v-card elevation="5" outlined height="170" width=80%>


    <v-list-item three-line>
      <v-list-item-content>
        <v-list-item-title class="headline mb-4">
         Order ID <v-spacer></v-spacer> 
        </v-list-item-title>
        <v-list-item-title class="headline mb-4">
          Order Date  
        </v-list-item-title>
        
        <v-list-item-title class="headline mb-4">
          Order Total
        </v-list-item-title>
      </v-list-item-content>
    </v-list-item>   
    </v-card>
  </v-row>


   <v-row align="center" justify="center" >
    <v-card elevation="4" outlined height="50" width=80% >

     <v-list-item one-line>
        <v-list-item-content>
          <v-list-item-title class="headline mb-4">
             View Details
          </v-list-item-title>
        </v-list-item-content>
      </v-list-item>
     
    </v-card>
   </v-row>
      
  <v-row> <v-col></v-col> </v-row>

</template>



  <template>
    <v-footer class="text-center" darkgrey padless> 

     <v-container>
      <v-row>
        <v-col cols="3"> 
        <v-btn icon> <v-icon> mdi-alphabetical </v-icon> </v-btn>
        <h6>Frendy</h6>
        </v-col>
        <v-col cols="3"> 
        <v-btn icon><v-icon> mdi-magnify </v-icon></v-btn>
        <h6>Search</h6>
        </v-col>
        <v-col cols="3"> 
        <v-btn icon> <v-icon> mdi-account-circle</v-icon></v-btn>
        <h6>Account</h6>
        </v-col>
        <v-col cols="3"> 
        <v-btn icon> <v-icon>  mdi-cart </v-icon> </v-btn>
        <h6>Cart</h6>
        </v-col>
     </v-row>
    </v-container>


    </v-footer>
  </template>

  </v-form>
</template>
 