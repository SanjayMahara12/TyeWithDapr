# TyeWithDapr
TyeWithDapr

----------------------------------
  Project Backend 
----------------------------------
dapr run --app-id backend  --app-port 5000 --dapr-http-port 3500 -- dotnet run   
dapr run --app-id backend  --app-port 5000 -- dotnet run                    

----------------------------------
  Project WebUi(FrontEnd that would consume backend services)
----------------------------------
dapr run --app-id frontend --app-port 5005 --dapr-http-port 3600 -- dotnet run
dapr run --app-id frontend --app-port 5005 -- dotnet run                 

----------------------------------
 Dapr Dashboard
----------------------------------
run command "dapr dashboard"
//this is to get a dapr UI interface to view and control the dapr sidecar apps

----------------------------------
 Tye
----------------------------------
run command "tye init" to initialize tye project configuration
creates tye.yaml --for structuring application together

