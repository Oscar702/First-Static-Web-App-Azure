# First-Static-Web-App-Azure
<H1> Creating Your First Static Web App on Azure </H1>
  
  <H2>Prerequisites</H2>
  <ul>
  <li>Azure subscription </li>
  <li> Github account </li></ul>
  
  <p> To start you mush have an Azure Portal account. If you don't here is the link https://azure.microsoft.com/en-us/free/ to get $200 worth of credit to use in 30days. You must also have a Github account, if you don't you can easily get an account by going to Github.com.</p>
  
  <p>In this turorial we will be creating our first Static Web App on Azure using an html file from a repository in Github.
  First thing is to create a repository on Github. On your browser type copy the following url
   https://github.com/Oscar702/az-static-web-app/generate.</p>
  
  
  <img src="https://i.imgur.com/rzW9oO1.png" alt="Github create repo"/>
  
  Next name your repository <strong><em>my-first-Static-web-app</em></strong>
  
  
  You may select public or private, it's up to you. This is for demonstration purposes only.
  
  Lastly click on <em>Create repository from Template</em>
  
  <img src="https://i.imgur.com/PvXQRQX.png" alt="github codefiles"/>
  
 Next step is to go to Azure Portal and in the search bar type Static Web App. 
  
  <img src="https://i.imgur.com/fg33q65.png" alt="selecting web static app" />
  
  Select create new static web app, and fill out the following.
  
  <img src="https://i.imgur.com/rgv28rA.png" alt="basics azure"/>
  
  <br> For Resource Group, select create new and name it Static Web App</br>
  
  <br>For Static web app details name it <em>my-first-static-web-app</em></br>
  <br>For Hosting Plan select Free</br>
  <br>Then select the region that is closest to you</br>
  <br>For deployment-source details select Github
    You might have to sign in to your Github account if this your first time usin Github on Azure</br>
  <br>For organization write your Github user name</br>
  <br>For repository write <strong>my-first-static-web-app</strong></br>
  <br>For branch select main</b>
  
  
  
  <img src="https://i.imgur.com/HnaOYHR.png" height="50%" width="50%"  alt="build details"/>
 <b>Build Details</b> 
 
  <br>Build Presets select Custom</br>
  <br>App location /src (that is where the HTML file is located)</br>
  <br>leave Api blank</br>
  <br>output location /src</br>
  
  
  
  
  Next select review and create
  if all looks good select create
  
  
 <img src="https://i.imgur.com/hA4J7rD.png" height="50%" width="50%"  alt="select create"/>
  
  
  Once deployment is complete select resource
  
  
  <img src="https://i.imgur.com/tYGOK2p.png" height="80%" width="80%"  alt="deployment complete"/>
  
  Next you will see the URL that Azure has created for you, click on the URL
  
  <img src="https://i.imgur.com/YlDzRhH.png" alt="selectURL"/>
  
  Once you click on the URL it should open a new tab and will have something similiar like in the image below
  
  <img src="https://i.imgur.com/cuwQupn.png" height="60%" width="60%"  alt="poem"/>
  
  Congratulations on creating your first static web page on azure. 
  As you can see Azure generates a domain name for us, but it is possible to have you own custom domain. First you you will have to purchase a domain name from domain registrar such as Godaddy.com or CheapNames.com. Next I suggest you follow visit the following link to see how you can have your purchased domain name on an Azure static web page. https://learn.microsoft.com/en-us/azure/static-web-apps/custom-domain?tabs=azure-dns&WT.mc_id=javascript-17844-cxa.
  
  Well that is it for this tutorial, if you do not wish to keep your static web app I suggest you delete your entire resource group so you do not accrue any charges.
  
  
  
  
  
 
