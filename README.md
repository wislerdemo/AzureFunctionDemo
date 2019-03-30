# AzureFunctionDemo

Notes on creating an Azure function app
1. Dont create it in Azure portal.  Use the template in VS.
2. You may get a 401 when you run it.  Try to set the "AuthorizationLevel.Function" in the line that defines the method to AuthorizationLevel.Anonymous if you have to to get it going
3. You may get a cors issue.  If so go in the portal and incude the domain or * in the cors configuration found in the Platform Features tab that is displayed when the function is selected
4. Remember to include the /api/<functionname>?<parmname>=<value> along with the domain name that is provided when the function is published to Azure
  

