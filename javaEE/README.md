# This folder contains all questiosn regarding JavaEE EJB Spring and so on


## Business logic is part of the program that encodes the real-world business rules

## constrain: compel or force someone to follow a particular course of action

## Business rules tell companies what they can do in detail

## Macro: large, related to the whole of something.

## Component in JEE: A javaEE component is a self-contained functional Software Unit that's assembled into a java EE application with its related classes and files that communicates with other components.

## Container: is an interface between a component adn the low-level platform with specific functionality that supports the component.

## Components(web, EJB, application client) must be assembled in a JAVAEE module and deployed into its container.

## Concern: something that's important to someone.


## JavaBeans is a class that fullfills the conditons:
  1. setter and getter
  2. default constructor without any arg
  3. implements serializable.
  
## Enterprise JavaBeans

## Application server vs web server
Quotes from:
https://www.google.de/search?ei=EO6FWp2aCo3LwAKClqjICA&q=application+server+vs+web+server&oq=application&gs_l=psy-ab.3.0.35i39k1j0i67k1j0l8.48618.49919.0.50511.11.11.0.0.0.0.169.1197.6j5.11.0....0...1c.1.64.psy-ab..0.11.1192....0.44QJkaSuXTU
```
Most of the times these terms Web Server and Application server are used interchangeably.

Following are some of the key differences in features of Web Server and Application Server:

    Web Server is designed to serve HTTP Content. App Server can also serve HTTP Content but is not limited to just HTTP. It can be provided other protocol support such as RMI/RPC
    Web Server is mostly designed to serve static content, though most Web Servers have plugins to support scripting languages like Perl, PHP, ASP, JSP etc. through which these servers can generate dynamic HTTP content.
    Most of the application servers have Web Server as integral part of them, that means App Server can do whatever Web Server is capable of. Additionally App Server have components and features to support Application level services such as Connection Pooling, Object Pooling, Transaction Support, Messaging services etc.
    As web servers are well suited for static content and app servers for dynamic content, most of the production environments have web server acting as reverse proxy to app server. That means while servicing a page request, static contents (such as images/Static HTML) are served by web server that interprets the request. Using some kind of filtering technique (mostly extension of requested resource) web server identifies dynamic content request and transparently forwards to app server

Example of such configuration is Apache Tomcat HTTP Server and Oracle (formerly BEA) WebLogic Server. Apache Tomcat HTTP Server is Web Server and Oracle WebLogic is Application Server.

In some cases the servers are tightly integrated such as IIS and .NET Runtime. IIS is web server. When equipped with .NET runtime environment, IIS is capable of providing application services.
```

### If you use package.* then all the classes and interfaces of this package will be accessible but not subpackages. 
