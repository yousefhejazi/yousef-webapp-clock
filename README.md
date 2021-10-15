[Yousef Hejazi](https://github.com/yousefhejazi)


## How to create a webapp using HTML
<br>
<br>


## 1) Make a working directory
```
cd $home

git clone https://github.com/WebDevSimplified/JavaScript-Clock.git webapp2021

cd webapp2021
```



## 2) install "serve" using npm (only once)

```
npm install serve --global
serve

```

## 3) Login to azure via powershell
```
az login

```

## 4)  Upload your app to Azure (Repeat on code change)
```
az webapp up --name "yousef-webapp-clock" --resource-group "yousef" --location "westeurope"  --html --launch-browser
```

## 5) # test on Azure
```
chrome https://yousef-webapp-clock.azurewebsites.net
```
