## Hi! Welcome to our showcase page.
Meet the Jeak framework for TeamSpeak 3 servers:  

> _Ever set up a Minecraft server with plugins?  
  We wanted to have this, just for TeamSpeak.  
  So we built just that!_ 
  
[![ShieldsIO](https://img.shields.io/github/license/jeakfrw/jeak-framework.svg?color=success&style=flat-square)](https://github.com/jeakfrw/jeak-framework/blob/bleeding-1.X.X/LICENSE)
[![ShieldsIO](https://img.shields.io/github/tag-pre/jeakfrw/jeak-framework.svg?color=yellow&style=flat-square)](https://github.com/jeakfrw/jeak-framework/releases)
![ShieldsIO](https://img.shields.io/maintenance/yes/2019.svg?style=flat-square)
[![ShieldsIO](https://img.shields.io/discord/533021399560880141.svg?style=flat-square)](https://discord.gg/DPYR5aB)    
_[Click to see more badges](https://github.com/jeakfrw/jeak-framework/#badges)_

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
The Jeak framework project is completely free to use (M.I.T. licensed) even commercially.  
We distribute all installation archives with extensive license information about our dependencies (__please check their licenses too, as we cannot give reliable legal advice__).  
_If you integrate the framework into your hosting business, feel free to ask for a partnership._
  
### How does Jeak accomplish this?
The framework contains many services that plugins can utilize to do what they need to do.  
Each service is only responsible for one functionality which results in very modular implementation code.  
Additionally, plugins can register their own services to provide other dependent plugins with their functionality.  
  
We believe that creating and freely distributing the project helps the bigger cause of improving TeamSpeak 3 experience for everyone.  
Although not enforced, we urge all plugin developers to do the same for their plugins and serve the community :)  
Even without developing a plugin, anyone can actively help the project by contributing by other means:
* Testing & submitting bug reports
* Sharing own knowledge and experience with the community (help others)
* Suggesting new features and ideas to keep the project moving forward
* Generally taking part in discussions about anything in the ecosystem - keep the minds fresh :)
  
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
* Documentation & Guides: [https://jeakbot.readme.io](https://jeakbot.readme.io)  
* Issues, Code & Planning: [https://github.com/jeakfrw/jeak-framework](https://github.com/jeakfrw/jeak-framework)  
* Plugins made by FearNixx Gaming: [https://gitlab.com/fearnixxgaming/jeakbot/](https://gitlab.com/fearnixxgaming/jeakbot/)
* ReadMe: [On GitHub](https://github.com/jeakfrw/jeak-framework/blob/bleeding-1.X.X/README.md)
* Support available on Discord: [https://discord.gg/DPYR5aB](https://discord.gg/DPYR5aB) (English/German)  
  _Yes, we know - but this is an easy way for OSS to provide support to you ':D_
* We live on TeamSpeak ^^: [ts.fearnixx.de](ts3server://ts.fearnixx.de) (German)  
  _(This is our community TS - it is not supposed for providing Jeak support!)_
* Our community: [https://fearnixx.de](https://fearnixx.de)
  _(German)_  
* Artifacts & Jars hosted on Nexus OSS: [https://nexus.fearnixx.de](https://nexus.fearnixx.de)
