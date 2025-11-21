# DA25D400_DAL_Kaggle_Competition

Name: Karan Kishore
Roll number: DA25D400

# DA5401 Metric Learning Challenge

Final solution for the DA5401 end-semester Kaggle challenge.  
Goal: predict a fitness score (1–10) for each *(metric, prompt, response)* triplet.

## Method Overview
- LaBSE embeddings for system, user, and response text  
- Provided Gemma metric-definition embeddings  
- Synthetic negative sampling (metric shuffling + low scores)  
- Cosine-similarity features between metric and text vectors  
- LightGBM regressor on combined features (~2600 dims)

## Performance
- Validation RMSE: **2.44**
- Test RMSE : **2.026**  
- Final Kaggle position: **11**

## Files
- `da25d400-code-kaggle-competition.ipynb` — full code  
- `DA25D400_DAL_report.pdf` — final LaTeX report 
