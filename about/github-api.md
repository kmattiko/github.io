An API is a Application Programming Interface

  - Authentication requests can be for obtaining user profile information for yourself or others. This could be something such as your user signing into the web app and the information is being pulled from the larger database. 
  - The three ways to authenticate are from Base, Token (header), and Token (parameter) 
  - You need an authentication for a website where you are storing any kind of sensitive data like logins 
  - If a user is unauthorized it will return a 401 (Unauthorized) until several failed attempts and then a 403 (Forbidden) will appear for a set amount of time
  - APIs for specific users can be gained by doing a ```$ curl -u https://api.github.com``` for a basic request. Sometimes this will not provide a detailed account of repositories
  - ```$ curl -i -u username -d '{"scopes":["public_repo"]}' https://api.github.com/authorizations``` can be used when wanting ot pull information for a specific repository
  - Activity APIs will allow you to pull how many followers, stars, watches, notifications, feeds, and events a user has
  - The Github Api limits how many authenticated and unauthenicated requests can be made in an hour. The numbers are 5k and 60 accordingly. 
  - It is possible to increase the number of unauthenticated requests can be increased by passing your apps Client ID and secret as part as a query string. 
  - If you reach your limit of requests you will start to recieve a 403 error until the time resets. You are able to check to see how many requests you have left to ensure you do not go over this limit. 
  - 30 items are pagnated by default when a request is made
  - by using the ```?page``` parameter up to 100 pages can be requested. 
  - the ```?per_page``` parameter can often return how many pages are available to be retrieved (...?)
  
  
