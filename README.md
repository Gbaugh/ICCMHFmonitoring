# Target Setting for Monitoring Using Aggregate Datasets (ICCMHFmonitoring)
Tools for monitoring iCCM using aggregate Health Facility data

Problem: The programme monitoring databases and other HMISs such as DHIS2 contain data that is aggregated, usually at the health facility level.  This allows basic reporting, but the aggregation hides problems in the system.  

Proposal: Using a metadata for each Health Facility, target population and intervention, a modelled dataset can used to produce a probable result against which the monthly facility data can be compared.  For ICCM the number of CHWs, the target population, and basic epidemiological data can be used to produce a ‘target range’ for each indicator, such as the expected number of cases presenting.  This will allow for a deeper understanding of the data and more targeted interventions by health professionals.  


Supplemental activities necessary:
•	Routine periodic surveys to update assumptions caregiver behaviour, such as careseeking.  
•	Periodic register reviews of source data to identify problem CHWs and data quality


Facility X
1.	Total cachement area covered by CHWs
2.	Fever rates at different times of year
3.	Careseeking behaviour in endline survey
4.	(criteria to calculate range minimum and maximum)
a.	Calculate target, then review across health facilities
b.	Algorithm for using historical data (twelve months, one month)
c.	Standard deviation for each step
d.	Reporting rate (must be 100% of CHWs reporting)
e. 

Endline Survey (%)			
  Careseeking from CORPs for fever	
  Received Assessment	Malaria Positivity	
  Received Treatment

Actual DHIS2 (n)				(or RAcE reports)
  Careseeking from CORPs for fever	
  Assessed	
  RDT +	
  Stock out for 7 consecutive days	
  Received Treatment

Calculated (n)		
  Careseeking from CORPs for fever	
  Positive RDT	
  Received Treatment
  
  Factors:
    Aggregate CHW U5 Population
    Careseeking
    Historical RDT+ rate for the site
    RDT+ to Received Treatment
    Standard deviation
  
  Product:
    Probability of the number reported is accurate (data quality)
    Probability of the number reported is in line with a well supported group of CHWs (programme quality)
