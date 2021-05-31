<template>

  <v-card>
      <v-col class="text-right">
        <v-card-title class="headline" >
          Welcome to the LA Gladiators FanPage
        </v-card-title>
      </v-col>
            
        <br>
        <v-btn>Test</v-btn>
        <br>
            <v-col class="text-right">
             <img src="/Download.png" width="400" alt="Doesn't work" class="mb-5"  /> 
            </v-col>

      <v-card-title class="headline">
       Ergebnisse der letzten Jahre:
      </v-card-title> <br>
        <ul>
         <li>Season 1 2018 - 7.Platz </li> <br>
         <li>Season 2 2019 - 5.Platz </li> <br>
         <li>Season 3 2020 - 2.Platz </li> <br>
         <li>Season 4 2021 (aktuell) - 10. Platz </li> 
       </ul>
         <br>
        <v-card-actions>
         <v-btn color="purple" nuxt to="/Overwatch"> Über Overwatch </v-btn> 
        </v-card-actions>

        <v-card-actions>
         <v-col class="text-right">
          <v-btn color="purple" nuxt to="/Team"> Mehr Infos über das aktuelle Team</v-btn>
         </v-col>
       </v-card-actions>
  </v-card>
</template>

