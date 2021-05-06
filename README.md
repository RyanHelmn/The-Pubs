
# The Pubs

A basic Umbraco v9 concept site which contains all of the pubs in the UK. That are listed...


## FAQ (kinda, I don't think anyone's asked these)

#### WTF Is This? 😒

Well, it's an Umbraco v9 site. A proof of concept more than anything, well something I want to try out because who doesn't love Umbraco and .NET Core.

#### Anything Special?

Not really. Has some nifty things in there that you, someone who wants to learn about Umbraco or are just viewing for the shits and giggs. This project is however, setup as a production website.
What do I mean by this?
- The CMS & Solution is structured how I would present it to a client
- The website could technically be used as a live website, in the sense of: it has all the nifty things like robots.txt, XML sitemap etc.


  
## Installation 

- Checkout the repo.
- Open the solution in your favourite IDE.

- If you're running this on Windows, you can use the SQL CE version of the website utilising the existing database. In this case, you can run the following commands and get started:
```bash 
  dotnet build
  dotnet run
```

- If you're running this on any other OS, you'll need to create your own SQL database.
- I'd recommend removing the Umbraco SQL CE Nuget package.
- Clear the ConnectionString from the appSettings.config.
- Then run the following commands:
```bash 
  dotnet build
  dotnet run
```
- Install the site on said database. Since the project has uSync installed you can just run the uSync import and get started. It also includes uSync content so expect all the site to be ready to rock and roll 🎉.
    
