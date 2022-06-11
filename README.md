# MechaCar Study with R

# 1: Linear Regression to Predict MPG

The below linear regression analysis shows the predictions of MechaCar prototypes using vehicle length, vehicle weight, spoiler angle, ground clearance and AWD as variables.  The screen shot is shown below.  
<img src="lin_regression"/>
 - The variables that had non-random amount of variance would be the vehicle_lenth and ground_clearance as shown by their P Values << 0.05 
 - The slope of the linear model is not zero as shown by the "Multiple R-squared" value of 0.7149 which indicates a correlation with the variables and mpg.  
 - The linear model somewhat predicts the mpg of MechaCar prototypes.  Our correlations show these factors (lenght & ground clearance mostly) play a role in determining the mpg but these are not the sole determing factors.  

# 2: Summary Statistics on Suspension Coils

The Total Summary figure shows the variance of 62.29 (below the 100 psi max limit) but in reviewing the breakout by lot we can see this is greatly influenced by lot 3 which has a variance of 170.29.   

Fig: Total Summary
<img src="total_summary.png"/>

Fig: Lot Summary
<img src="lot_summary.png"/>


# 3: T-Test on Suspension Coils
T-Test Results for Lot 1  
<img src="T-Test_Lot1.png"/>

T-Test Result for Lot 2 
<img src="T-Test_Lot2.png"/>


T-Test Result for Lot 3 
<img src="T-Test_Lot3.png"/>

## Study Design: MechaCar vs Competition





