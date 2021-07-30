<template>
 <div class="container">
   <div style="margin-right:7.4cm" class="justify-space-between">
     <v-row justify="center" align="center">
       <v-col align-items-left cols="25" sm="8" md="6">
         <v-card
         class="rounded-lg"
          style="margin-top : 30px ; padding : 8px"
          elevation="12" 
          max-width="700" 
          width="700"
         >
           <v-card-title>
            <h2>Extra Curricular</h2> 
          </v-card-title>
          <v-card-subtitle>
            <br>
            <p>
            <v-icon color="red" >mdi-circle</v-icon>
            <v-icon color="green" >mdi-circle</v-icon>
            <v-icon color="blue" >mdi-circle</v-icon>
            <v-icon color="yellow" >mdi-circle</v-icon>
            </p>
          </v-card-subtitle>
          
           <v-card-text>
             <v-container class="pa-4 text-center">
               <v-row
                  class="fill-height"
                  align="center"
                  justify="center"
                >
                  <v-col
                    cols="12"
                    md="6"
                  >
                    <v-hover v-slot="{ hover }" >
                      <v-card
                        
                      :elevation="hover ? 12 : 2"
                      :class="{'on-hover':hover}">
                        <v-img
                          :src="require('@/assets/image/Screen Shot 2564-07-30 at 23.13.40.png')"
                          height="300px"
                          width="700px"
                        >
                          <v-card-title class="text-h3 black--text">
                            <v-row
                              class="fill-height flex-column"
                              justify="space-between"
                            >
                              <h3 class="mt-4 subheading text-left">
                                School Cheerleader 
                              </h3>
                            </v-row>
                          </v-card-title>
                        </v-img>
                      </v-card>
                    </v-hover>
                  </v-col>

                  <v-col
                    cols="12"
                    md="6"
                  >
                    <v-hover v-slot="{ hover }" >
                      <v-card
                        
                      :elevation="hover ? 12 : 2"
                      :class="{'on-hover':hover}">
                        <v-img
                          :src="require('@/assets/image/Screen Shot 2564-07-30 at 23.54.17.png')"
                          height="300px"
                          width="700px"
                        >
                          
                        </v-img>
                      </v-card>
                    </v-hover>
                  </v-col>

                  <v-col
                    cols="12"
                    md="9"
                  >
                    <v-hover v-slot="{ hover }" >
                      <v-card
                        
                      :elevation="hover ? 12 : 2"
                      :class="{'on-hover':hover}">
                        <v-img
                          :src="require('@/assets/image/Screen Shot 2564-07-30 at 23.53.48.png')"
                          height="300px"
                          width="700px"
                        >
                          
                        </v-img>
                      </v-card>
                    </v-hover>
                  </v-col>
               </v-row>
             </v-container>
           </v-card-text>
         </v-card>


         
       </v-col>
       
       
       
     </v-row>
   </div>
 </div>
</template>
