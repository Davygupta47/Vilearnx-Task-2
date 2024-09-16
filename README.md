VilearnX offers a dynamic internship experience, providing students with hands-on exposure to AI-driven projects, mentorship from industry experts, and a collaborative environment to develop skills and build a strong professional network.
Dear VilearnX Team,
        I wanted to take a moment to express my sincere gratitude for the opportunity to intern at VilearnX. I am so grateful to have had the chance to work alongside, and I have learned so much from each one of the given tasks for DATA ANALYTICS and MACHINE LEARNING. 
Thanking you, 
Dwaipayan Dasgupta

# Vilearnx-Task-2
This particular task is a linear regression model that can predict the Sale Price of houses in the Ames Housing dataset with a Mean Squared Error (MSE) of {mse:.2f} and an R-squared (R2) of {r2:.2f}. The model's performance is visualized through a scatter plot of actual vs. predicted Sale Prices and a distribution of residuals.
The implemented linear regression model has been trained and evaluated on the Ames Housing dataset, and its performance has been visualized. The model's accuracy can be assessed based on the evaluation metrics and visualizations provided.
The results are visualized through a scatter plot of actual vs. predicted Sale Prices, which shows the model's predictions and their corresponding actual values and a distribution of residuals, which provides insight into the model's errors and their distribution.

OUTPUT:
 Order        PID  MS SubClass MS Zoning  Lot Frontage  Lot Area Street  \
0      1  526301100           20        RL         141.0     31770   Pave   
1      2  526350040           20        RH          80.0     11622   Pave   
2      3  526351010           20        RL          81.0     14267   Pave   
3      4  526353030           20        RL          93.0     11160   Pave   
4      5  527105010           60        RL          74.0     13830   Pave   

  Alley Lot Shape Land Contour  ... Pool Area Pool QC  Fence Misc Feature  \
0   NaN       IR1          Lvl  ...         0     NaN    NaN          NaN   
1   NaN       Reg          Lvl  ...         0     NaN  MnPrv          NaN   
2   NaN       IR1          Lvl  ...         0     NaN    NaN         Gar2   
3   NaN       Reg          Lvl  ...         0     NaN    NaN          NaN   
4   NaN       IR1          Lvl  ...         0     NaN  MnPrv          NaN   

  Misc Val Mo Sold Yr Sold Sale Type  Sale Condition  SalePrice  
0        0       5    2010       WD           Normal     215000  
1        0       6    2010       WD           Normal     105000  
2    12500       6    2010       WD           Normal     172000  
3        0       4    2010       WD           Normal     244000  
4        0       3    2010       WD           Normal     189900  

[5 rows x 82 columns]
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 2930 entries, 0 to 2929
Data columns (total 82 columns):
...

[8 rows x 39 columns]
Mean Squared Error (MSE): 0.00
R-squared (R2): 1.00
Output is truncated. View as a scrollable element or open in a text editor. Adjust cell output settings...

<ipython-input-18-fcaec929eabf>:48: UserWarning: 

`distplot` is a deprecated function and will be removed in seaborn v0.14.0.

Please adapt your code to use either `displot` (a figure-level function with
similar flexibility) or `histplot` (an axes-level function for histograms).

For a guide to updating your code to use the new functions, please see
https://gist.github.com/mwaskom/de44147ed2974457ad6372750bbe5751

  sns.distplot(y_test - y_pred)
![image](https://github.com/user-attachments/assets/79219a21-a041-4de5-a8e2-f15b4cd3afd4)
![image](https://github.com/user-attachments/assets/ee4afde7-6b11-468b-a761-a5540e5bb37a)

