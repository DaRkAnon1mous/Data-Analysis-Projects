## Question:
### How many of them responding project requests below average and which states are performing best in terms of donations per project?

- To understand this question we will find out max and min 
- Assuming df is your DataFrame with 'Projects' and 'Donations' columns
- First, let's ensure there are no NaNs or infinite values in the data
![image](https://github.com/user-attachments/assets/ed2d424f-6926-4712-9c5c-286c4ffb9de9)

- Check if there's enough data to perform the fit
- Scale the data if necessary
- Calculate the slope and intercept for the linear model
-  Define the x values for the linear model line (min and max of Projects)
-  Calculate the corresponding y values using the linear equation y = mx + c
![image](https://github.com/user-attachments/assets/27035fe6-5eca-4192-b446-eca6e1f75813)
![image](https://github.com/user-attachments/assets/e571f0c9-ec4b-4fd3-a3e0-309f9272e630)


-  Combine the plots
![image](https://github.com/user-attachments/assets/f09327c0-5de9-430a-83e2-a53df77282d6)

## Output
![image](https://github.com/user-attachments/assets/d951bac2-211e-4031-99d8-b9433ccdf1d8)
- dots below the line shows that the states have not good donation
- and dots above have better donations
- the line represents the boundary line of good and bad
