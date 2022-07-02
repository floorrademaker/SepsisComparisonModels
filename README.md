# SepsisComparisonModels

The files included in this repository show the process models of the treatment of sepsis. The data has been retrieved from the 4TU platform; 
Mannhardt, Felix (2016): Sepsis Cases - Event Log. 4TU.ResearchData. Dataset. https://doi.org/10.4121/uuid:915d2bfb-7e84-49ad-a286-dc35f063a460 

The models have been created through ProM and BPMNDiffViz.

1. Relative Process Models
  These models have been created in ProM by using the Inductive Visual Miner (IVM) plugin and choosing the relative path representation.
  Included models:
  
  - RelativeBelow65.png = the process model of the patients younger than 65 
  - RelativeBelow65Between65and85.png = the process model of the patients between 65 and 85, including 65
  - RelativeOlderThan84.png = the process model of the patients older than 84

  - RelativeSIRSfalse.png = the process model of patients that have met 0 or 1 criteria of the SIRS criteria
  - RelativeSIRStrue.png = the process model of patients that have met 2, 3 or 4 criteria of the SIRS criteria
  
  - RelativeShorterThanWeek.png = the process model of patients that went through a treatment that took less than 7 days
  - RelativeLongerThanWeek.png = the process model of patients that went through a treatment that took more than 7 days
  
2. Comparison Models
  These models visualize the comparison of two models. These models are created by using BPMNDiffViz and choosing the TabuSearch algorithm for calculating the GED.
  Included models:
  
  - ComparisonBelow65_Between65and85.png = shows the comparison of the process model of patients younger than 65 and the process model of patients between 65 and 85, including 65. 
  GED = 44
   - ComparisonBelow65_Olderthan84.png = shows the comparison of the process model of patients younger than 65 and the process model of patients older than 84.
  GED = 54
  - ComparisonBetween65and85_OlderThan84.png = shows the comparison of the process model of patients between 65 and 85, including 65 and the patients older than 84. 
  GED = 56
  
  - SIRSBelowVSHigh.png = shows the comparison of the process models of patients either meeting 2 or more of the SIRS criteria or not.
  GED = 58
  
  - ShorterVsLonger.png = shows the comparison of the process models of patients either having a treatment with a duration of less or more than 7 days.
  GED = 98
