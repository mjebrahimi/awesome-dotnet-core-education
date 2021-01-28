# Awesome .Net Core Education [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Collection of useful articles and resources to learning and practicing about .Net Core and its related technologies. this repository will update continuously, keep yourself up to date. 😉


Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/mehdihadeli/awesome-dotnet-core-education/blob/master/contributing.md) pages first.

Thanks to all [contributors](https://github.com/mehdihadeli/awesome-dotnet-core-education/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

Check out my [blog](https://dotnetuniversity.com) or find me on [Linkedin](https://www.linkedin.com/in/mehdihadeli/) or [Twitter](https://twitter.com/mehdi_hadeli)!



## Contents

- [Awesome Dotnet Core Education](#Awesome-Dotnet-Core-Education)
  - [.Net5](#.Net5)
  - [.Net Standard](#.Net-Standard)
  - [Generic Host & Web Host](#Generic-Host-&-Web-Host)
  - [LifeCycle](#LifeCycle)
  - [Hosting](#Hosting)
  - [Kestrel](#Kestrel)
  - [Middleware](#Middleware)
  - [Configuration](#Configuration)
  - [Options Pattern](#Options-Pattern)
  - [Grpc](#Grpc)
  - [WebSockets](#WebSockets)
  - [HttpClient](#HttpClient)
  - [WEB API](#WEB-API)
  - [Hosted Service](#Hosted-Service)
  - [Test Host & WebApplicationFactory](#Test-Host-&-WebApplicationFactory)
  - [Routing](#Routing)
  - [Dependency Injection](#Dependency-Injection)
  - [Mapping](#Mapping)
  - [Benchmarking](#Benchmarking)

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Mehdi Hadeli](https://github.com/mehdihadeli) has waived all copyright and related or neighboring rights to this work.

## .Net 5

#### Articles

[Announcing .NET 5.0 - DevBlogs](https://devblogs.microsoft.com/dotnet/announcing-net-5-0/)

[What's new in .NET 5 - Microsoft](https://docs.microsoft.com/en-us/dotnet/core/dotnet-five)

[Introducing C# Source Generators - DevBlogs](https://devblogs.microsoft.com/dotnet/introducing-c-source-generators/)

[Performance Improvements in .NET 5 - DevBlogs](https://devblogs.microsoft.com/dotnet/performance-improvements-in-net-5/)

[The Many Flavors of .NET - Sean Killeen](https://flavorsof.net)



## .Net Standard

#### Articles

[.NET Standard - Microsoft](https://docs.microsoft.com/en-us/dotnet/standard/net-standard)

#### Videos

[Big Changes in .NET 5, C# 9, and Visual Studio 2019 - IAmTimCorey](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=zjVgQNfAEOs)



## Generic Host & Web Host

#### Articles

- [ASP.NET Core Web Host](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/web-host?view=aspnetcore-5.0)

- [.NET Generic Host in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/generic-host?view=aspnetcore-5.0)

- [USING HOSTBUILDER AND THE GENERIC HOST IN .NET CORE MICROSERVICES](https://www.stevejgordon.co.uk/using-generic-host-in-dotnet-core-console-based-microservices)

- [Generic Host Builder in ASP .NET Core 3.1](https://wakeupandcode.com/generic-host-builder-in-asp-net-core-3-1/)

- [The ASP.NET Core Generic Host: namespace clashes and extension methods](https://andrewlock.net/the-asp-net-core-generic-host-namespace-clashes-and-extension-methods/)

- [Avoiding Startup service injection in ASP.NET Core 3](https://andrewlock.net/avoiding-startup-service-injection-in-asp-net-core-3/)

- [IHostingEnvironment vs IHostEnvironment - obsolete types in .NET Core 3.0](https://andrewlock.net/ihostingenvironment-vs-ihost-environment-obsolete-types-in-net-core-3/#asp-net-core-merges-with-the-generic-host)

- [.NET Generic Host](https://docs.microsoft.com/en-us/dotnet/core/extensions/generic-host)

- [Understanding .NET Generic Host Model](https://sahansera.dev/dotnet-core-generic-host/)

- [Exploring the new project file, Program.cs, and the generic host](https://andrewlock.net/exploring-the-new-project-file-program-and-the-generic-host-in-asp-net-core-3/)

- [Introducing IHostLifetime and untangling the Generic Host startup interactions](https://andrewlock.net/introducing-ihostlifetime-and-untangling-the-generic-host-startup-interactions/)

- [Exploring Program.cs, Startup.cs and CreateDefaultBuilder in ASP.NET Core 2 preview 1](https://andrewlock.net/exploring-program-and-startup-in-asp-net-core-2-preview1-2/)

- [WebHostBuilder](https://girishgodage.in/blog/customize-webhostbuilder)

- [Customizing ASP.​NET Core Part 11: WebHostBuilder](https://asp.net-hacker.rocks/2019/01/30/customizing-aspnetcore-11-webhostbuilder.html)

#### Samples

- [https://github.com/andrewlock/blog-examples/tree/master/updating-test-host-to-3-0](https://github.com/andrewlock/blog-examples/tree/master/updating-test-host-to-3-0)



## LifeCycle 

#### Articles

- [ASP.NET CORE ANATOMY – HOW DOES USESTARTUP WORK?](https://www.stevejgordon.co.uk/aspnet-core-anatomy-how-does-usestartup-work)

- [ASP.NET CORE ANATOMY (PART 2) – ADDMVC](https://www.stevejgordon.co.uk/asp-net-core-anatomy-part-2-addmvc)

- [ASP.NET CORE ANATOMY (PART 3) – USEMVC](https://www.stevejgordon.co.uk/asp-net-core-anatomy-part-3-addmvc)

- [ASP.NET CORE ANATOMY (PART 4) – INVOKING THE MVC MIDDLEWARE](https://www.stevejgordon.co.uk/invoking-mvc-middleware-asp-net-core-anatomy-part-4)



## Hosting

#### Articles

- [5 ways to set the URLs for an ASP.NET Core app](https://andrewlock.net/5-ways-to-set-the-urls-for-an-aspnetcore-app/)

- [Adding host filtering to Kestrel in ASP.NET Core](https://andrewlock.net/adding-host-filtering-to-kestrel-in-aspnetcore/)

- [ASP. NET Core - Hosting](https://girishgodage.in/blog/customize-hosting)

- [Customizing ASP.NET Core Part 12: Hosting](https://asp.net-hacker.rocks/2019/04/29/customizing-aspnetcore-12-hosting.html)



## Kestrel

#### Articles

- [Kestrel web server implementation in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/kestrel?view=aspnetcore-5.0)

- [.NET Core 3.0 AllowSynchronousIO Workaround](https://khalidabuhakmeh.com/dotnet-core-3-dot-0-allowsynchronousio-workaround)



## Middleware

#### Articles

- [DEEP DIVE: HOW IS THE ASP.NET CORE MIDDLEWARE PIPELINE BUILT?](https://www.stevejgordon.co.uk/how-is-the-asp-net-core-middleware-pipeline-built)

- [ASP.NET Core Middleware](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-5.0)

- [Understanding your middleware pipeline with the Middleware Analysis package](https://andrewlock.net/understanding-your-middleware-pipeline-with-the-middleware-analysis-package/)

- [Exploring IStartupFilter in ASP.NET Core](https://andrewlock.net/exploring-istartupfilter-in-asp-net-core/)

- [Creating an endpoint from multiple middleware in ASP.NET Core 3.x](https://andrewlock.net/creating-an-endpoint-from-multiple-middleware-in-aspnetcore-3/)

- [Converting a terminal middleware to endpoint routing in ASP.NET Core 3.0](https://andrewlock.net/converting-a-terminal-middleware-to-endpoint-routing-in-aspnetcore-3/)

- [Middlewares](https://girishgodage.in/blog/customize-middleware)

- [Customizing ASP.​NET Core Part 06: Middlewares](https://asp.net-hacker.rocks/2018/10/08/customizing-aspnetcore-06-middlewares.html)



## Configuration

#### Articles

- [Configure ASP.NET Core MVC](https://www.programmingwithwolfgang.com/configure-asp-net-core-mvc/)

- [Configuration in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-5.0)

- [Configuration providers in .NET](https://docs.microsoft.com/en-us/dotnet/core/extensions/configuration-providers)

- [ASP. NET Core - Customize Configuration](https://girishgodage.in/blog/customize-configuration)

- [Creating a custom ConfigurationProvider in ASP.NET Core to parse YAML](https://andrewlock.net/creating-a-custom-iconfigurationprovider-in-asp-net-core-to-parse-yaml/)

- [Customizing ASP.​NET Core Part 02: Configuration](https://asp.net-hacker.rocks/2018/09/24/customizing-aspnetcore-02-configuration.html)

#### Libraries

- [NetEscapades.Configuration](https://github.com/andrewlock/NetEscapades.Configuration)


#### Samples

- [https://github.com/WolfgangOfner/MVC-Core-Configure](https://github.com/WolfgangOfner/MVC-Core-Configure)



## Options pattern

#### Articles

- [Options pattern in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/options?view=aspnetcore-5.0)

- [How to use the IOptions pattern for configuration in ASP.NET Core RC2](https://andrewlock.net/how-to-use-the-ioptions-pattern-for-configuration-in-asp-net-core-rc2/)



## Grpc

#### Articles




## WebSockets 

#### Articles

- [Understanding WebSockets with ASP.NET Core](https://sahansera.dev/understanding-websockets-with-aspnetcore-5/)

- [Using Web Sockets with ASP.NET Core](https://www.meziantou.net/using-web-sockets-with-asp-net-core.htm)

- [WebSockets support in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets?view=aspnetcore-5.0)



## SignalR

#### Articles

- [Use streaming in ASP.NET Core SignalR](https://docs.microsoft.com/en-us/aspnet/core/signalr/streaming?view=aspnetcore-5.0)



## HttpClient

#### Articles

- [SENDING AND RECEIVING JSON USING HTTPCLIENT WITH SYSTEM.NET.HTTP.JSON](https://www.stevejgordon.co.uk/sending-and-receiving-json-using-httpclient-with-system-net-http-json)

- [.NET 5: Exploring System.Net.Http.Json namespace](https://anthonygiretti.com/2020/10/03/net-5-exploring-system-net-http-json-namespace/)



## WEB API

#### Articles

- [ASP.NET Core 5 Route to Code: Taking advantage of Microsoft.AspNetCore.Http json extensions](https://anthonygiretti.com/2020/09/29/asp-net-core-5-route-to-code-taking-advantage-of-microsoft-aspnetcore-http-json-extensions/)

- [Nano services with ASP.NET Core or how to build a light API](https://anthonygiretti.com/2020/06/29/nano-services-with-asp-net-core-or-how%20-to-build-a-light-api/)

- [Beautiful and compact Web APIs with C# 9, .NET 5.0 and ASP.NET Core](https://www.strathweb.com/2020/10/beautiful-and-compact-web-apis-with-c-9-net-5-0-and-asp-net-core/)

- [Building microservices with ASP.NET Core (without MVC)](https://www.strathweb.com/2017/01/building-microservices-with-asp-net-core-without-mvc/)

#### Samples

- [https://github.com/featherhttp/framework](https://github.com/featherhttp/framework)

- [https://github.com/featherhttp/tutorial](https://github.com/featherhttp/tutorial)

- [https://github.com/filipw/net50-webapi-samples](https://github.com/filipw/net50-webapi-samples)

- [https://github.com/ardalis/ApiEndpoints](https://github.com/ardalis/ApiEndpoints)



## Hosted Service

#### Articles

- [IMPLEMENTING IHOSTEDSERVICE IN ASP.NET CORE 2.0](https://www.stevejgordon.co.uk/asp-net-core-2-ihostedservice)

- [Background tasks with hosted services in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services?view=aspnetcore-3.1&tabs=visual-studio)

- [ASP. NET Core - IHostedService and BackgroundService](https://girishgodage.in/blog/customize-hostedservices)

- [Customizing ASP.​NET Core Part 05: HostedServices](https://asp.net-hacker.rocks/2018/10/04/customizing-aspnetcore-05-hostedservices.html)



## Test Host & WebApplicationFactory

#### Articles

- [Converting integration tests to .NET Core 3.0](https://andrewlock.net/converting-integration-tests-to-net-core-3/)

- [Using custom startup class with ASP.NET Core integration tests](https://gunnarpeipman.com/aspnet-core-integration-test-startup/)

- [Using custom appsettings.json with ASP.NET Core integration tests](https://gunnarpeipman.com/aspnet-core-integration-tests-appsettings/)



## Routing

#### Articles



## Dependency Injection

#### Articles

- [Having Fun with Microsoft IoC Container for .NET Core](https://sahansera.dev/dotnet-core-ioc-container/)

- [ASP. NET Core - Dependency-injection](https://girishgodage.in/blog/customize-dependency-injection)

- [Customizing ASP.​NET Core Part 03: Dependency Injection](https://asp.net-hacker.rocks/2018/09/27/customizing-aspnetcore-03-dependency-injection.html)



## Mapping

#### Libraries 

- [Mapster](https://github.com/MapsterMapper/Mapster)
> A fast, fun and stimulating object to object Mapper. 

#### Videos

- [Mapster, the best .NET mapper that you are (probably) not using](https://www.youtube.com/watch?v=UIslFVEHkzA)

- [Domain to Contract mapping with Automapper | ASP.NET Core 5 REST API Tutorial 20](https://www.youtube.com/watch?v=1Dz5Lfo6mqo)


## Benchmarking

#### Libraries

[BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet)
> Powerful .NET library for benchmarking

#### Videos

- [Benchmarking C# code using BenchmarkDotNet](https://www.youtube.com/watch?v=EWmufbVF2A4)

- [Analyzing performance with BenchmarkDotNet - ASP.NET Core: From 0 to overkill](https://www.youtube.com/watch?v=8JOC8kN_WbU)

