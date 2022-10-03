# Mecha_Car_R_Analysis

## Deliverable 1: Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/107448860/193497709-284b65a6-fc94-4484-bce0-bcbf30528800.png)

![image](https://user-images.githubusercontent.com/107448860/193497733-eb4e8265-b1af-4a80-96d9-97770fe26d04.png)

Taking a look at the outputs from the analysis, we can see that the vehicle length and vehicle ground clearance are providing the least amount of random variance to our model, which essentially means if is going to have an impact on the MPG of the MechaCar. 

Based on the P-Value, the slope of our linear model is not going to be zero.

The information provided indicates that the model that we have created should predict the mpg of the MechaCar effectively. 

## Deliverable 2: Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/107448860/193498204-cb708c99-7e6b-47c3-938c-ea6b0a3c2be6.png)

![image](https://user-images.githubusercontent.com/107448860/193498225-ba3d45e1-7876-4e7f-ae5b-2b8a9b27d982.png)

![image](https://user-images.githubusercontent.com/107448860/193498313-89c77045-39ec-41ff-b3bf-9cec41081668.png)

![image](https://user-images.githubusercontent.com/107448860/193498331-ab2811c4-9e8f-4f87-b7f3-8db6107eff05.png)

We take a look at the Var_PSI and the number is 62.29, which is within the 100 PSI requirement that is provided. This should meet the demands that the design specifications that were assigned. Lot 1 and 2 are also well within the limits, but lot 3 exceeds the number that is provided. In the graph we can see the difference that is impacting our average from lot 3.

## Deliverable 3: T-Tests on Suspension Coils

![image](https://user-images.githubusercontent.com/107448860/193498637-c46c240f-f6f7-4e9c-bfe1-3904ca6f9894.png)

When taking a look at the t-tests, we can see that something was very different in lot 3 compared to lot 1 and 2. The P-value is fairly high within lot 1 and 2 comparatively to lot 3's p-value of .04. This does not fall within the common significance level of 0.05. This means that we have to reject this test. 

## Deliverable 4: Study Design: MechaCar vs Competition

A couple of things that would be interesting for manufacturers to take a look at when comparing vehicles are MPG, engine type, safety ratings, and resale values. This can determine how a car performs and how long they can last even if they are running at a high level. 

Null Hypothesis: MechaCar is priced correctly based on the type of car.

Alternative Hypotheses: MechaCar is not priced corrected based on the type of car.

Using a multiple linear regression would use these variables and test them correctly.
