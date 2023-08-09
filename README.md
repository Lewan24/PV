Private repositories that could be used via contact

There is the list of repositories that i have checked as private coz of data like logins and passwords in configs.
I can share them after deleting vulnerable data. These projects are the most advanced and complex with implemented
some features like advanced security system, authorization etc.

## PostWithFacebookGraphApi
  - App for food groceries. You create there the menu, generate image and post on facebook
  
## UseFacebookGraphApi_dotnet
  - Actual project for testing posting images, texts to facebook page
  
## SystemZamowienDotNET
  - Application like storage management but with orders, auth, roles etc. Project created for company
  purposes its actually working on public site where the personel is working.
  
## LauncherApp
  - Launcher app for games or programs. There you can update program, reinstall, check files, run app etc.
  
## NewsLetter
  - Simple newsletter with accessible configurator to send mass emails. You can send html templates,
  just text, mass addresses, everything work async, every error throws to container where you 
  have a visible problems. On the end you can try send again to ppl where the addresses throwed an error.

## EmployeePanel
  - Big application made for company. Includes flexible system of modules (applications made inside project as the pages), services, controllers,
    identity system with custom roles.
  - Project has also implemented Prometheus and Grafana for storing data bout application like information about errors, bad requests, counter for each controller method,
    memory allocation etc.
  - Mediator (source generated nuget packet for better optimalization and less memory allocation) inside of most of controllers
  - Application is built in WASM technology with .NET 7.
  - I made also integrity with docker to host all containers like the main application, databse with phpmyadmin, prometheus and grafana.
  - Server has also external Tests project to test controllers methods (in progress of implementing tests to all methods).
