# digital-traces-tp3
Small python app on google trend with flask and deployed with deta

## Requirements
```
pip install -r requirements.txt
```

## Deploy
You can deploy the micro using the following deta commands </br>
First install deta using 
```
iwr https://get.deta.dev/cli.ps1 -useb | iex
```
Login with 
```
deta login
```
Initialize the micro
```
deta new --python first_micro
deta new --project <your-project> 
```
Finally you can deploy the changes using 
```
deta deploy
```
