# Step 1
 Import mlflow code from
 https://mlflow.org/docs/latest/tutorials-and-examples/tutorial.html
 
# Step 2
 pip install -r requirements.txt
 
# Step 3
run main.py

# Step 4
For other values for alpha and l1_ratio
>python examples/sklearn_elasticnet_wine/train.py <alpha> <l1_ratio>

# Step 5
### To push code on git hub
**Initialize git by** git init

**Add all folder by** git add . && git commit -m "   "

git remote add origin {github respo url}

**Create as main branch by** git branch -m main

git push origin main
