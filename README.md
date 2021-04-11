# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
Multiple regression was performed on MechaCar data. Looking at the analysis, it is clear that vehicle weight, spoiler angle and AWD have less chance of affecting MPG since their P-value's are higher.Since vehicle length and ground clearance have lower p-values, thus these variables might have more impact on MPG.
Also, r-squared value of multiple linear regression is 0.714 which means that approx 71% of all MPG predictions can be correct when using linear model. Our p-value is much smaller than significance level 0.05 which means that there is sufficient evidence to reject the null hypothesis and therefore the overall slope of linear model is not zero.

![Challenge1](https://user-images.githubusercontent.com/76858662/114288874-0ad1b780-9a41-11eb-82c3-d5181e3f6399.PNG)

![Challenge2](https://user-images.githubusercontent.com/76858662/114288875-0e653e80-9a41-11eb-88a6-ee89545bf4d3.PNG)

![Challenge3](https://user-images.githubusercontent.com/76858662/114288878-10c79880-9a41-11eb-90dc-5eb356f024f5.PNG)

## Suspension Coil
In this part of the challenge, after testing the data, it seems that lot 1 and 2 are under the design specifications which is variance of suspension coil should nto exceed more than 100 pounds. Lot 3 has exceeded the maufacturer's specified variance. The mean, median and SD of each lot can be seen in the summery table below.

![Challenge5](https://user-images.githubusercontent.com/76858662/114288957-f3df9500-9a41-11eb-8b24-648263afda35.PNG)

![Challenge4](https://user-images.githubusercontent.com/76858662/114288960-f7731c00-9a41-11eb-9c89-fde241f9f822.PNG

## T-test
T-test was performed to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch. Our p-value is 0.06 which is above the significance level of 0.05 which suggest that the means can be statistically similar. The test also has a 95% confidence interval of 1497.507 1500.053, which would mean the population mean of 1500 falls under the 95% confidence interval.

![Challenge6](https://user-images.githubusercontent.com/76858662/114289316-ee377e80-9a44-11eb-9b64-c8238a73d29e.PNG)

![Lot1Ttest](https://user-images.githubusercontent.com/76858662/114289324-f5f72300-9a44-11eb-8789-f81c4772b434.PNG)

![Lot2Ttest](https://user-images.githubusercontent.com/76858662/114289328-ff808b00-9a44-11eb-9255-73a619582899.PNG)

![Lot3Ttest](https://user-images.githubusercontent.com/76858662/114289333-04453f00-9a45-11eb-9348-acaab693fc99.PNG)

## Study Design: MechaCar vs Competition
The team wants to further analyze and quantify how the MechaCar performs against the competition. There are few factors that people consider while buying a car and the top one is MPG - comparing fuel efficiencies of MechaCar prototypes with their competitiors. Other metrics that are considered are horsepower and size of the engine. 

H0 - stating that there is no statistical difference between MechaCar prototypes MPG and competitors.
Ha- stating that the true mean of MechaCar prototypes's MPG dataset greater than that of our competitors.

The data that is needed would be MechaCar prototypes that have varying design specifications from vehicle lengths and ground clearance as it was clearly shown that these specifications affect MPG the most. These specifications are then matched with competitiors car to see who wins the race of fuel efficiency. After collecting data, we will use paired T-test. This is to compare population of all types of competitor vehicles and call each subset of manufacturing lots to check which lot is not meeting standards.
If the p value is less than 0.05






