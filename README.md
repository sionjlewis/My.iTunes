# My.iTunes
This is an exploration of Angular 2, TypeScript, ASP.NET MVC 5, NPM packages, ASP.NET Web API 2, Entity Framework 6, CORS, Authentication and Unit Testing with Moq, Ninject and Jasmin. 

The solution uses all these technologies to extract data from a local iTunes library with a Console Application (My.iTunes.Import), which then POSTs the data to a Web API (My.iTunes.WebAPI). The Web API implements Entity Framework to CRUD two MS SQL databases and is consumed by the Website (My.iTunes.Client). The Website gives a User the ability to search for, and view iTunes Tracks, to Authenticate, add comments and ratings and update and delete their own comments and ratings (implementing authorised). 

Other aspects I may explore are LESS and Bundling for CSS & JS files.

For a simplified solution, which demonstrates how Angular 2 and ASP.NET MVC 5 can coexist, please see: https://github.com/sionjlewis/Hello.Angular.World 

For more information: http://www.sjlewis.com
