<h1> Database for Psychological Onlinestudies</h1>
(this is still work in progress and will be updated regularly)

This is a database for online studies conducted at the Institute for Psychology at Kiel University, Germany. 
Here, you can find experimental and analysis scripts for the following studies:


<h3>Pilot Study: Risk Assessment</h3>
- Participants were asked to write down a dilemma scenario with 2 options for action and to rate the risk of each option.
- Experimental script (lab.js):
- Analysis script (R): <br> https://github.com/MMarieSchuckart/Kiel_Online_Studies_Database/blob/master/risk_pilot/pilot1_Read_SQlite


<h3>Redundant Signals Effect</h3>
- replication of the RSE (Todd, 1912): shorter reaction times when responding to multisensory (here: audiovisual) compared to unisensory stimuli (here: visual and auditory)
- 1 training block, 3 main blocks with 90 trials each
- Experimental script (lab.js):<br> 
- Analysis scripts (R):  
      - for the lab study:<br> 
https://github.com/MMarieSchuckart/Kiel_Online_Studies_Database/blob/master/RSE/Read_CSV_lab <br> 
      - for the online study:<br> 
https://github.com/MMarieSchuckart/Kiel_Online_Studies_Database/blob/master/RSE/Read_SQLite_online <br> 


<h3>Sound Induced Flash Illusion (SIFI)</h3>
- SIFI: Illusionary perception of a double flashe instead of a single one when a flash is presented together with two short beeps
- replication of the SIFI under different levels of cognitive load, manipulated via n-back-tasks (Michail & Keil, 2018)
- 4 main Blocks:
  - Block 1: SIFI (Baseline) (42 trials --> 10 Illusion trials)
  - Block 2: 0-back + SIFI (42 trials --> 10 Illusion trials)
  - Block 3: 1-back + SIFI (42 trials --> 10 Illusion trials)
  - Block 4: 2-back + SIFI (42 trials --> 10 Illusion trials)<br>
      --> There's a short training block before each main block<br>     
- Experimental script for the German online part (as a lab.js file; you can easily turn this into a lab study, too):<br>  https://github.com/MMarieSchuckart/Kiel_Online_Studies_Database/blob/master/SIFI_nback/exp_online <br>
- Analysis script (R): 
      - for the online study:<br>        https://github.com/MMarieSchuckart/Kiel_Online_Studies_Database/blob/master/SIFI_nback/Read_SQLite_online <br> 
      - for the lab study: <br> 
      https://github.com/MMarieSchuckart/Kiel_Online_Studies_Database/blob/master/SIFI_nback/Read_CSV_lab <br> 
      - comparison of the datasets: <br>
      https://github.com/MMarieSchuckart/Kiel_Online_Studies_Database/blob/master/SIFI_nback/stats_compare_datasets <br><br>





