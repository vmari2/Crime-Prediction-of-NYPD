CRIME PREDICTION OF NYPD


Business Problem


Problem Context
Predict the number of offenses for a given precinct within the next three months,based on historical crime data of the New York Police Department (NYPD) by using Negative Binomial Regression
Content The dataset covers the data of all crimes reported to the New York Police Department from 2006 to the end of last year i.e.,2019. This is a large dataset consisting of 6.98 million records with 35 attributes.Given, the large size, we could filter data to a more manageable size and per our project requirement.

####Features#####

    #cmplnt_num        - randomly generated complaint number              
    #cmplnt_fr_dt      - exact date of crime occurance         
    #cmplnt_fr_tm      - exact time of crime occurance          
    #addr_pct_cd       - precinct in which the incident occured                  
    #ofns_desc         - Offense description                           
    #crm_atpt_cptd_cd  - Indicator of whether crime was successfully completed or attempted    
    #law_cat_cd        - Level of offense: felony, misdemeanor, violation     
    #boro_nm           - The name of the borough in which the incident occurred       
    #loc_of_occur_desc - Location of crime occurence      
    #prem_typ_desc     - Description of premises    
    #juris_desc        - Description of jurisdiction code   
    #jurisdiction_code - Jurisdiction responsible for incident.   
    #susp_age_group    - Suspect’s Age Group   
    #susp_race         - Suspect’s Race Description    
    #susp_sex          - Suspect’s Sex Description    
    #patrol_boro       - Name of the patrol borough in which crime occurred   
    #vic_age_group     - Victim’s Age Group      
    #vic_race          - Victim's Race Description    
    #vic_sex           - Victim's Sex Description      
    #cmplnt_to_dt      - End Date of Crime Occurence  
    #cmplnt_to_tm      - End Time of Crime Occurence

  Dataset:
  https://www1.nyc.gov/site/nypd/stats/crime-statistics/citywide-crime-stats.page.
    
