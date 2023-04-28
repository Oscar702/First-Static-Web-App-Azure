# First-Static-Web-App-Azure
<H1> Creating Your First Static Web App on Azure </H1>
  
  <H2>Prerequisites</H2>
  <ul>
  <li>Azure subscription </li>
  <li> Github account </li></ul>
  
  <p> In this turorial we will be creating our first Static Web on Azure using a code from a repository in Github.
  First thing is to create a repository on Github. On your browser type copy the following url
   https://github.com/Oscar702/az-static-web-app/generate.
  
  
  <img src="https://i.imgur.com/rzW9oO1.png" alt="Github create repo"/>
  
  Next name your repository <strong><em>my-first-Static-web-app</em></strong>
  
  
  You may select public or private, it's up to you. This for demonstration purposes only.
  
  Lastly click on <em>Create repository from Template</em>
  
  <img src="https://i.imgur.com/PvXQRQX.png" alt="github codefiles"/>
  
  First thing is go to Azure Portal and in the search bar type Static Web App. 
  
  <img src="https://i.imgur.com/fg33q65.png" alt="selecting web static app" />
  
  Select create new static web app, and fill out the following.
  
  <img src="https://i.imgur.com/rgv28rA.png" alt="basics azure"/>
  
  For Resource Group, select create new and name it Static Web App
  
  For Static web app details name it <em>my-first-static-web-app</em>
  For Hosting Plan select Free
  Then select the region that is closest to you
  For deployment-source details select Github
  You might have to sign in to your Github account if this your first time usin Github on Azure
  For organization write your Github user name
  For repository write <strong>my-first-static-web-app</strong>
  For branch select main
  
  
  
  <img src="https://i.imgur.com/HnaOYHR.png" alt="build details"/>
  For Build Details 
  Build Presets select Custom
  App location /src
  leave Api blank
  output location /src
  
  
  
  
  Next select review and create
  if all looks good select create
  
  
 <img src="https://i.imgur.com/hA4J7rD.png" alt="select create"/>
  
  
  Once deployment is complete select resource
  
  
  <img src="https://i.imgur.com/tYGOK2p.png" alt="deployment complete"/>
  
  Next you will see the URL that Azure has created for you, click on the URL
  
  <img src="https://i.imgur.com/YlDzRhH.png" alt="selectURL"/>
  
  Once you click on the URL it should open a new tab and will have something similiar like in the image below
  
  <img src="https://i.imgur.com/cuwQupn.png" alt="poem"/>
  
  Congratulations on creating your first static web page on azure. 
  as you can see Azure generate a domain name for us, but it is possible to have you own custom domain. First you you will have to purchase a domain name a domain registrar such as Godaddy.com or CheapNames.com Next I suggest you follow visit the following link to see how you can have your preferred domain name on an Azure static web page. https://learn.microsoft.com/en-us/azure/static-web-apps/custom-domain?tabs=azure-dns&WT.mc_id=javascript-17844-cxa.
  
  Well that is it for this tutorial, if you do not wish to keep your static web app I suggest you delete your entire resource group so you do not accrue any charges.
  
  
  
  
  
 
