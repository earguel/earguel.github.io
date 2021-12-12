---
layout: post
title:  "Exploraroty Regression-Vote Republican 2016"
date:   2021-12-01 13:27:31 -0500
categories: jekyll update
---
******************************************************************************
Choose 1 of 8 Summary
       Highest Adjusted R-Squared Results       
AdjR2     AICc   JB K(BP)  VIF   SA   Model           
 0.45 -4572.62 0.00  0.00 1.00 0.00  -PNEVERMARRIED***
 0.32 -3917.58 0.00  0.00 1.00 0.00  +PREPPARTY***    
 0.24 -3562.98 0.00  0.40 1.00 0.00  -PCOLLEGEDEG***  
       Passing Models       
AdjR2 AICc JB K(BP) VIF SA   Model
******************************************************************************
Choose 2 of 8 Summary
                Highest Adjusted R-Squared Results               
AdjR2     AICc   JB K(BP)  VIF   SA   Model                            
 0.55 -5207.69 0.00  0.00 1.08 0.00  -PNEVERMARRIED***  -PCOLLEGEDEG***
 0.52 -5025.99 0.00  0.00 1.00 0.00  +PREPPARTY***  -PCOLLEGEDEG***    
 0.52 -4974.21 0.00  0.00 1.00 0.00  -AVEHHINC16***  -PNEVERMARRIED*** 
       Passing Models       
AdjR2 AICc JB K(BP) VIF SA   Model
******************************************************************************
Choose 3 of 8 Summary
                       Highest Adjusted R-Squared Results                       
AdjR2     AICc   JB K(BP)  VIF   SA   Model                                           
 0.60 -5581.15 0.00  0.00 1.86 0.00  +PREPPARTY***  -PNEVERMARRIED***  -PCOLLEGEDEG***
 0.56 -5260.49 0.00  0.00 1.57 0.00  -PSENIORS***  -PNEVERMARRIED***  -PCOLLEGEDEG*** 
 0.56 -5239.89 0.00  0.00 1.71 0.00  -AVEHHINC16***  +PREPPARTY***  -PNEVERMARRIED*** 
       Passing Models       
AdjR2 AICc JB K(BP) VIF SA   Model
******************************************************************************
Choose 4 of 8 Summary
                                Highest Adjusted R-Squared Results                               
AdjR2     AICc   JB K(BP)  VIF   SA   Model                                                            
 0.62 -5702.28 0.00  0.00 2.19 0.00  -PSENIORS***  +PREPPARTY***  -PNEVERMARRIED***  -PCOLLEGEDEG***   
 0.60 -5601.26 0.00  0.00 1.94 0.00  +PREPPARTY***  +PBLUECOLLAR***  -PNEVERMARRIED***  -PCOLLEGEDEG***
 0.60 -5583.41 0.00  0.00 1.86 0.00  -POPDENS_CY  +PREPPARTY***  -PNEVERMARRIED***  -PCOLLEGEDEG***    
       Passing Models       
AdjR2 AICc JB K(BP) VIF SA   Model
******************************************************************************
Choose 5 of 8 Summary
                                       Highest Adjusted R-Squared Results                                      
AdjR2     AICc   JB K(BP)  VIF   SA   Model                                                                          
 0.62 -5721.77 0.00  0.00 2.28 0.00  -PSENIORS***  +PREPPARTY***  +PBLUECOLLAR***  -PNEVERMARRIED***  -PCOLLEGEDEG***
 0.62 -5717.04 0.00  0.00 3.11 0.00  -AVEHHINC16***  -PSENIORS***  +PREPPARTY***  -PNEVERMARRIED***  -PCOLLEGEDEG*** 
 0.62 -5714.58 0.00  0.00 2.28 0.00  -DIVERSITY16***  -PSENIORS***  +PREPPARTY***  -PNEVERMARRIED***  -PCOLLEGEDEG***
       Passing Models       
AdjR2 AICc JB K(BP) VIF SA   Model
******************************************************************************
************** Exploratory Regression Global Summary (PCT_GOP) ***************

              Percentage of Search Criteria Passed             
Search Criterion                    Cutoff Trials # Passed % Passed
Min Adjusted R-Squared              > 0.50    218      109    50.00
Max Coefficient p-value             < 0.05    218      149    68.35
Max VIF Value                       < 7.50    218      218   100.00
Min Jarque-Bera p-value             > 0.10    218        0     0.00
Min Spatial Autocorrelation p-value > 0.10     18        0     0.00

------------------------------------------------------------------------------

       Summary of Variable Significance       
Variable      % Significant % Negative % Positive
PREPPARTY            100.00       0.00     100.00
PBLUECOLLAR          100.00       0.00     100.00
PNEVERMARRIED        100.00     100.00       0.00
PCOLLEGEDEG          100.00     100.00       0.00
DIVERSITY16           90.91      97.98       2.02
AVEHHINC16            83.84      66.67      33.33
PSENIORS              81.82      58.59      41.41
POPDENS_CY            62.63     100.00       0.00

------------------------------------------------------------------------------

     Summary of Multicollinearity    
Variable       VIF Violations Covariates
AVEHHINC16    3.21          0 --------  
DIVERSITY16   1.48          0 --------  
POPDENS_CY    1.14          0 --------  
PSENIORS      1.81          0 --------  
PREPPARTY     1.84          0 --------  
PBLUECOLLAR   1.91          0 --------  
PNEVERMARRIED 2.54          0 --------  
PCOLLEGEDEG   3.69          0 --------  

------------------------------------------------------------------------------

                                        Summary of Residual Normality (JB)                                       
      JB    AdjR2         AICc    K(BP)      VIF       SA   Model                                                      
0.000080 0.343913 -4028.393997 0.000000 1.409057 0.000000  -DIVERSITY16***  +PSENIORS***  +PREPPARTY***                
0.000052 0.340556 -4013.535122 0.000000 1.249703 0.000000  -DIVERSITY16***  +PREPPARTY***                              
0.000001 0.359835 -4103.743576 0.000000 1.447605 0.000000  -DIVERSITY16***  -POPDENS_CY***  +PSENIORS***  +PREPPARTY***

------------------------------------------------------------------------------

                                           Summary of Residual Spatial Autocorrelation (SA)                                          
      SA    AdjR2         AICc       JB    K(BP)      VIF   Model                                                                          
0.000000 0.619761 -5721.773234 0.000000 0.000000 2.281085  -PSENIORS***  +PREPPARTY***  +PBLUECOLLAR***  -PNEVERMARRIED***  -PCOLLEGEDEG***
0.000000 0.619181 -5717.037356 0.000000 0.000000 3.113061  -AVEHHINC16***  -PSENIORS***  +PREPPARTY***  -PNEVERMARRIED***  -PCOLLEGEDEG*** 
0.000000 0.618880 -5714.580962 0.000000 0.000000 2.283534  -DIVERSITY16***  -PSENIORS***  +PREPPARTY***  -PNEVERMARRIED***  -PCOLLEGEDEG***

------------------------------------------------------------------------------
                    Table Abbreviations                     
AdjR2 Adjusted R-Squared                                     
AICc  Akaike's Information Criterion                         
JB    Jarque-Bera p-value                                    
K(BP) Koenker (BP) Statistic p-value                         
VIF   Max Variance Inflation Factor                          
SA    Global Moran's I p-value                               
Model Variable sign (+/-)                                    
Model Variable significance (* = 0.10; ** = 0.05; *** = 0.01)
------------------------------------------------------------------------------
