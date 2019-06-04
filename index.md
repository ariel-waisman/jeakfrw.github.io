## Hi! Welcome to our showcase page.
Meet the Jeak framework for TeamSpeak 3 servers:  

> _Ever set up a Minecraft server with plugins?  
  We wanted to have this, just for TeamSpeak.  
  So we built just that!_ 

### What is the Jeak framework?
The Jeak framework is a new and open source framework written in Java. It allows any developer to create plugins that interact with a TeamSpeak server.  
We aim to reduce the burden by taking care of many, usually tedious, things that an own application would have to implement.  
With Jeak, __developers can focus on what they really want to do: Code their awesome feature!__  
  
Plugins can communicate with the framework via an extensive plugin API which covers every part of the framework and provides stable and reliable contracts for plugin developers to work with.  
  
### How does Jeak accomplish this?
The framework contains many services that plugins can utilize to do what they need to do.  
Each service is only responsible for one functionality which results in very modular implementation code.  
Additionally, plugins can register their own services to provide other dependent plugins with their functionality.  
  
### What services do currently exist?
The following services are currently available for plugins to use:
* __Basic injections__  
* __(Chat) Commands__
* __Sending mails via. SMTP__
* __User profiles__
* __Permissions__
  * TeamSpeak 3
  * Custom plugin permissions
* __Configuration__
* __Database-connection__
  * Low-level (``DataSource``, sql statements, ...)
  * High-level (Hibernate integration)
* __Notifications__
* __Localization__
* __Caches__
  * Channels on server
  * Clients on server
* __Users__ (clients who are offline)

