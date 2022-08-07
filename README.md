# toronto-housing
House Toronto


+ https://id.heroku.com/login

# How it works:
+ File deployment structure
```
     |---- 1. Model (trained by Randomforest)
     |---- 2. Runtime/requirement.txt : create evironment Python 3.8
     |---- 3. Website: HTML (input box: information, output: prices)
     |---- 4. Write on Flask (deployment)
```
+ Deployment: 
  https://toronto-housing-prices.herokuapp.com/
  
```
     |---- 1. Create Heroku account
     |---- 2. Connect with Github account (verification)
     |---- 3. Select right branch (main)
     |---- 4. Deploy and debuged
```
comrpess package into 1 runfile: 144.3M

Building log:
```
    -----> Building on the Heroku-20 stack
    -----> Using buildpack: heroku/python
    -----> Python app detected
    -----> Using Python version specified in runtime.txt
     !     Python has released a security update! Please consider upgrading to python-3.8.13
           Learn More: https://devcenter.heroku.com/articles/python-runtimes
    -----> No change in requirements detected, installing from cache
    -----> Using cached install of python-3.8.12
    -----> Installing pip 22.1.2, setuptools 60.10.0 and wheel 0.37.1
    -----> Installing SQLite3
    -----> Installing requirements with pip
    -----> Discovering process types
           Procfile declares types -> web
    -----> Compressing...
           Done: 144.3M
    -----> Launching...
           Released v5
           https://toronto-housing-prices.herokuapp.com/ deployed to Heroku
    This app is using the Heroku-20 stack, however a newer stack is available.
    To upgrade to Heroku-22, see:
    https://devcenter.heroku.com/articles/upgrading-to-the-latest-stack
```
## Deloyment image:
![Herokuapp_result0](https://user-images.githubusercontent.com/100484606/183279077-7f07baf8-32ce-4125-adc0-c5daea62fccd.JPG)

### Prediction result 1:
![Herokuapp_result1](https://user-images.githubusercontent.com/100484606/183279103-9aa0379e-3501-4101-a2c0-5068c226b58d.JPG)

### Predicted result 2:
![Herokuapp_result2](https://user-images.githubusercontent.com/100484606/183279125-5e8cde2f-ebf6-494c-afce-54cea9efb51c.JPG)


