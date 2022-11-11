# API-template
Premade template to make building API easier

# Table Of Conent
* [Introduction](https://github.com/Hy0tic/API-template#API-template)
* [Get Started](https://github.com/Hy0tic/API-template#get-started)
* [Structure of API](https://github.com/Hy0tic/API-template#Structure-Of-The-API)

# Get Started
Prerequisite: Have [.NET 6](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) installed
1. Open the terminal the directory where the project will be
2. Execute these three commands
``` 
git pull https://github.com/Hy0tic/API-template.git
cd API
dotnet run
```
# Structure Of The API
There are four project folders: API, BL(business layer), DL(data layer), and Test.
By default, the API only reference the BL folder and the BL folder only reference the DL folder. 
