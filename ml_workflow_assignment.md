 ML Workflow Assignment

# Task 1

1. **Label:**
  The label is `repeat_purchase_flag`.  

  *Justification:* 
  This column shows what we are trying to predict — whether the customer buys again within 30 days..

2. **Column causing data leakage:**
  The column `discount_used_on_repeat_order` would introduce data leakage. 
  
  *Justification:* 
  This information is only known after the repeat purchase happens, so using it would give the model unfair future knowledge.


# Task 2

1. **Create a baseline model**  
   
   *Why it matters:* A baseline (e.g., predicting the majority class or using simple heuristics) provides a reference point to evaluate whether complex models like gradient boosting are actually adding value.

2. **Auditing and preparing the dataset**  
   *Why it matters:* Checking data quality, handling missing values, and ensuring no leakage or bias is critical before training. Without this step, the model may learn spurious patterns or produce misleading results.
