## Hi! Welcome to our showcase page.
Meet the Jeak framework for TeamSpeak 3 servers:  

> _Ever set up a Minecraft server with plugins?  
  We wanted to have this, just for TeamSpeak.  
  So we built just that!_ 

### What is the Jeak framework?
#### For everyone
The Jeak framework is a new and open source framework written in Java.  
It allows users to enhance their TeamSpeak 3 Server by installing plugins.  
Plugins can be installed just like plugins for Minecraft - by dragging a Jar-file into the "plugins" directory.  
Choose exactly what you want for your server - it's all yours!  
Some plugins are already available for download - developed and released by us. :)

#### For developers
It allows any developer to create plugins that interact with a TeamSpeak server.  
We aim to reduce the burden by taking care of many, usually tedious, things that an own application would have to implement.  
With Jeak, __developers can focus on what they really want to do: Code their awesome feature!__  
  
Plugins can communicate with the framework via an extensive plugin API which covers every part of the framework and provides stable and reliable contracts for plugin developers to work with.  
  
#### For hosting providers
The Jeak framework is completely free to use (M.I.T. licensed) even commercially.  
We distribute all installation archives with extensive license information about our dependencies.  
_If you integrate the framework into your hosting business, feel free to ask for a partnership for exclusive support!_
  
### How does Jeak accomplish this?
The framework contains many services that plugins can utilize to do what they need to do.  
Each service is only responsible for one functionality which results in very modular implementation code.  
Additionally, plugins can register their own services to provide other dependent plugins with their functionality.  
  
### What services do currently exist?
The following services are currently available for plugins to use:
* __Basic injections__  
  _Do not worry about how to get services; let us provide them to you._  
* __(Chat) Commands__  
  _Quickly register a listener for a specific user command._
  (More refinement is planned.)
* __Sending mails via. SMTP__  
  _We will take care of authorization, transport, etc. - you focus on the message._
* __User profiles__  
  _Store additional information about users and even merge multiple TS3 identities into one profile._
* __Permissions__  
  _Just ask: "Is this user allowed to do this" and we'll work that our for you._
  * TeamSpeak 3
  * Custom plugin permissions
* __Configuration__  
  _Need a configuration? No problem, we'll give you one. No need to worry about format, location, loading, saving, etc._
* __Database-connection__  
  _We will take care of credentials and connection pooling, you focus on your queries._
  * Low-level (``DataSource``, sql statements, ...)
  * High-level (Hibernate integration)  
    _Hibernate will even take care of your queries, while you focus on your business objects._
* __Notifications__  
  _Do not even check whether or not a client is actually online/available, just tell us to notify him._ (More refinement is planned.)
* __Localization__  
  _Languages are hard! So we ask the server owners to decide what the actual messages are supposed to be. ~~Identifiers are cooler anyways~~._
* __Caches__  
  _Just ask us, who and what is on the server. No need to query TS3 every time we need a client._
  * Channels on server
  * Clients on server
* __Users__ (clients who are offline)  
  _Need to do something with a user who is not online? There you go~_

### Links
* Documentation & Guides: https://jeakbot.readme.io  
* Issues, Code & Planning: https://github.com/jeakfrw/core-framework
* Plugins made by FearNixx Gaming: https://gitlab.com/fearnixxgaming/jeakbot/
* ReadMe: [On GitHub](https://github.com/jeakfrw/core-framework/blob/bleeding-1.X.X/README.md)