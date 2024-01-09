### Step 1
- ##### change directory to ml-backend
- `cd ml-backend`

### Step 2
- ##### initialize backend env
- `python -m venv backend`

### Step 3
- ##### install requirements
- `pip install -r requirements.txt`

### Step 4
- ##### start api server 
- `python .\api.py`

### Step 5
- ##### cheack the api endpoint
- ##### `localhost:5000/predict/personal` with json 
-  {
    "RevolvingUtilizationOfUnsecuredLines": 0.964673,
    "age": 40,
    "NumberOfTime30-59DaysPastDueNotWorse": 3,
    "DebtRatio": 0.382965,
    "MonthlyIncome": 13700,
    "NumberOfOpenCreditLinesAndLoans": 9,
    "NumberOfTimes90DaysLate": 3,
    "NumberRealEstateLoansOrLines": 1,
    "NumberOfTime60-89DaysPastDueNotWorse": 1,
    "NumberOfDependents": 2
 } 

### Step 6
- ##### come back to root directry
- ##### `cd ..`

### Step 7
- ##### change directory to web-app
- ##### `cd web-app`

### Step 8
- ##### install dependencies
- ##### `npm install`

### Step 9
- ##### start web-server
- ##### `node app.js`