# mercedes_benz_bench_time

# Create an ML algorithm that can accurately predict the time a car will spend on the test bench based on the vehicle configuration

# Agenda<br/>
1. If for any column(s), the variance is equal to zero, then you need to remove those variable(s)<br/>
2. Check for null and unique values for test and train sets<br/>
3. Apply label encoder for categorical variables<br/>
4. Perform dimensaionlity reduction with PCA<br/>
5. Predict the test_df values using xgboost<br/>

# Steps performed for solution
Technologies used : python (NumPy, Pandas ,scikit-learn)<br/>
Model used        : Random Forest<br/>
Evaluation done   : RMSE 9.131376983037843<br/>
