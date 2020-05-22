# Database for Psychological Onlinestudies
(this is still work in progress and will be updated regularly)

This is a database for online studies conducted at the Institute for Psychology at Kiel University, Germany. 
Here, you can find experimental and analysis scripts for the following studies:

# Redundant Signals Effect
- replication of the RSE (Todd, 1912): shorter reaction times when responding to multisensory (here: audiovisual) compared to unisensory stimuli (here: visual and auditory)
- 1 training block, 3 main blocks with 90 trials each
- Experimental script (lab.js):
- Analysis script (R): 

# Sound Induced Flash Illusion (SIFI)
- SIFI: Illusionary perception of a double flashe instead of a single one when a flash is presented together with two short beeps
- replication of the SIFI under different levels of cognitive load, manipulated via n-back-tasks (Michail & Keil, 2018)
- 4 main Blocks:
  - Block 1: SIFI (Baseline) (42 trials --> 10 Illusion trials)
  - Block 2: 0-back + SIFI (42 trials --> 10 Illusion trials)
  - Block 3: 1-back + SIFI (42 trials --> 10 Illusion trials)
  - Block 4: 2-back + SIFI (42 trials --> 10 Illusion trials)
      --> There's a short training block before each main block     
- Experimental scripts (lab.js):

      - for the online study: https://github.com/MMarieSchuckart/Kiel_Online_Studies_Database/blob/master/SIFI_nback/Read_SQLite_online
      - for the lab study: 
      https://github.com/MMarieSchuckart/Kiel_Online_Studies_Database/blob/master/SIFI_nback/Read_CSV_lab
      - comparison of the datasets: 


- Analysis script (R): 

# Pilot Study: Risk Assessment
- Participants were asked to write down a dilemma scenario with 2 options for action and to rate the risk of each option.
- Experimental script (lab.js):
- Analysis script (R): 

