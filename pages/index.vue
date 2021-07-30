<template id="templat_">
<div class="container">
  <div style="margin-right : 7.4cm" class="justify-space-between">
      <v-row justify="center" align="center">
        <v-col cols="25" sm="8" md="6">
          <v-card
          class="rounded-lg"
          style="margin-top : 30px; background-color : white"
          elevation="12" 
          max-width="700" 
          width="700">
            <v-row>
              <v-col>
                  <div class="Propics">
                      <v-img 
                      class="rounded-lg"
                      :src="require('@/assets/image/Propics_intoCoopIntern.png')"
                      style="width:310px ; margin : 23px ; border-radius : 300/2"
                      contain
                      />
                  </div>
                  <div>
                    <v-progress-linear
                      color="teal"
                      buffer-value="0"
                      value="20"
                      stream
                    ></v-progress-linear>
                  </div>
                  <p id="caption">
                    READY TO GO ON A NEW ADVENTURE
                    <v-icon color="teal">mdi-exclamation-thick</v-icon>
                  </p>
              </v-col>

              <v-col>
                <v-row>
                  <div style="margin-top : 25px">
                    
                    <v-sheet
                    :rounded="rounded"
                    color="white"
                    elevation="7"
                    height="110"
                    width="300"
                    
                    >
                      <v-card-title >
                        <h2>Komgrich Srisak</h2>
                        
                      </v-card-title>

                      <v-card-subtitle >
                        <p>A Software Engineering student
                          <br><v-icon color="red" >mdi-circle</v-icon>
                        <v-icon color="green" >mdi-circle</v-icon>
                        <v-icon color="blue" >mdi-circle</v-icon>
                        <v-icon color="yellow" >mdi-circle</v-icon>
                        </p>
                      
                        
                      </v-card-subtitle>
                      
                        
                        

                    </v-sheet>
                    
                    <v-card-text>
                        <v-list style="background-color : white">

                          <v-list-item>
                            
                            <v-list-item-title>
                              &nbsp;
                                <v-sheet 
                                class="rounded-lg"
                                style="padding : 25px ;"
                                color="green"
                                absolute 
                                >
                                  <v-row class="white--text">
                                  
                                    <v-icon color="yellow">mdi-phone-forward</v-icon>
                                  
                                    <h3>&nbsp;+66 89 437 7122 </h3>
                                  
                                  </v-row>
                                </v-sheet>
                              
                            </v-list-item-title>
                          </v-list-item>

                          <v-list-item>
                            <v-list-item-title>
                              &nbsp; 
                              <a href="mailto:6131305035@lamduan.mfu.ac.th" ><v-btn absolute><v-icon color="#FF1744">mdi-email</v-icon>&nbsp; Send me your email</v-btn></a>
                            </v-list-item-title>
                          </v-list-item>

                          <v-list-item>
                            <v-list-item-title>
                              &nbsp; 
                              <a target="blank" href="https://www.linkedin.com/in/komgrich-srisak-2b84791b0" ><v-btn absolute><v-icon color="blue">mdi-linkedin</v-icon>&nbsp; My LinkedIn</v-btn></a>
                            </v-list-item-title>
                          </v-list-item>

                        </v-list>

                    </v-card-text>
                  </div>
                </v-row>
                <v-row>
                  
                </v-row>
              </v-col>

            </v-row>
          </v-card>
        </v-col>
      </v-row>

      <v-row justify="center" align="center">
        <v-col align-items-center cols="25" sm="8" md="6">
          <v-card
          class="rounded-lg"
          style="margin-top : 30px ; padding : 8px"
          elevation="12" 
          max-width="700" 
          width="700">
          <v-card-title>
            <h2>Previous Education</h2> 
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
            <div>
             <v-timeline dense>
               <v-timeline-item
                  color="orange lighten-3"
                  fill-dot
                  right
                  icon='mdi-star'
                  icon-color="grey"
                >
                  <v-card>
                    <v-card-title class="orange lighten-3">
                      <div>
                      <h2 class="text-h4 orange--text font-weight-bold">
                        Naresuan University Secondary 
                        <br>
                        Demonstration school
                      </h2>
                      </div>
                      <div>
                      <v-img
                        class="rounded-lg"
                        :src="require('assets/image/logo_n.png')"
                        width="60"
                        height="60"
                        /></div>
                      
                    </v-card-title>
                    <v-container>
                      <v-row>
                        <v-col
                          cols="12"
                          md="10"
                        >
                        <div style="padding : 5px">
                          <h1>2013 - 2018</h1>
                        </div>
                        <div style="padding : 5px">
                          <h2>Science - Mathematics program</h2>
                        </div>
                        </v-col>
                        <v-col
                          class="hidden-sm-and-down text-right"
                          md="2"
                        >
                          <v-icon color="orange lighten-3" size="64">
                            mdi-school
                          </v-icon>
                        </v-col>
                      </v-row>
                    </v-container>
                  </v-card>
               </v-timeline-item>
               <v-timeline-item
                  color="yellow accent-1"
                  fill-dot
                  right
                  icon='mdi-heart'
                  icon-color="red"
                >
                  <v-card>
                    
                    <v-card-title style="background-image: url('https://en.mfu.ac.th/fileadmin/_processed_/d/0/csm_05_c9be468c31.jpg') " class="yellow accent-1">
                      <div>
                        <v-img
                        class="rounded-lg"
                        :src="require('assets/image/logo_mfu_3d_colour.png')"
                        width="80"
                        height="100"
                        />
                      <h2 class="text-h4 red--text font-weight-light">
                        
                    
                        Mae Fah Luang <br>University
                        
                      </h2>
                      </div>
                      <br>
                      
                    </v-card-title>
                    <v-container>
                      <v-row>
                        <v-col
                          cols="12"
                          md="10"
                        >
                        <div style="padding : 5px">
                          <h1>2018 - 2022</h1>
                        </div>
                        <div style="padding : 5px">
                          <h2>Bachelor of Science, Software Engineering</h2>
                        </div>
                        </v-col>
                        <v-col
                          class="hidden-sm-and-down text-right"
                          md="2"
                        >
                          <v-icon color="red" size="64">
                            mdi-xml
                          </v-icon>
                        </v-col>
                      </v-row>
                    </v-container>
                  </v-card>
               </v-timeline-item>
             </v-timeline>
            </div>
          </v-card-text>
          </v-card>
        </v-col>
      </v-row>
  </div>

</div>
</template>

<style scoped>
 #caption{
   color : teal; 
   padding : 7px; 
   margin-left : 27px;
  
 }
 v-card {
   width: "600%";
   
 }
 .Propic{
   border-radius: 300/2;
 }
</style>
