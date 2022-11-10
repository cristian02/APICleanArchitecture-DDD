#  APICleanArchitecture-DDD

Rest API in .Net 6.0 with Clean Architecture and Domain Driven Design 

<p>Commands executed</p>
<ol>
  <li>dotnet --version </li> Check out your dotnet version 
  <li>dotnet new sln -o CleanArchitectureDDD </li> Create a solution 
  <li>dotnet new webapi -o CleanArchitectureDDD.Api </li> Create and include web api in solution
  <li>dotnet new classlib -o CleanArchitectureDDD.Constracts </li> Create and include library in solution 
  <li>dotnet new classlib -o CleanArchitectureDDD.Infrastructure</li> Create and include library in solution 
  <li>dotnet new classlib -o CleanArchitectureDDD.Architecture</li> Create and include library in solution
  <li>dotnet new classlib -o CleanArchitectureDDD.Domain</li> Create and include library in solution 
  <li>dotnet sln add **/*.csproj</li> Add project into sln 
  <li>dotnet add ./CleanArchitectureDDD.Api reference ./CleanArchitectureDDD.Constracts ./CleanArchitectureDDD.Application</li> Associate references 
  <li>dotnet add ./CleanArchitectureDDD.Infrastructure reference ./CleanArchitectureDDD.Application</li> Associate reference
  <li>dotnet add ./CleanArchitectureDDD.Application reference ./CleanArchitectureDDD.Domain</li> Associate reference
  <li>dotnet add ./CleanArchitectureDDD.Api reference ./CleanArchitectureDDD.Infrastructure</li> Associate reference
  <li>dotnet run --project ./CleanArchitectureDDD.Api</li> Execute el webAPI 
  
</ol>

## Extensions 
Rest Client in VS Code (REST Client allows you to send HTTP request and view the response in Visual Studio Code directly.)

<!-- CONTACT -->
## Contact
Cristian Martínez Hernández 

[![LinkedIn][linkedin-shield]][linkedin-url]

## Reference
https://www.youtube.com/watch?v=fhM0V2N1GpY&t=858s


<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/cristian-mart%C3%ADnez-hern%C3%A1ndez-08043699/
