---
TOCTitle: ModuleInitializer Members
Title: 'ModuleInitializer Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.ModuleInitializer'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430850(v=PandP.50)'
---

Prism Class Library

ModuleInitializer Members
=========================

Include Protected Members
Include Inherited Members

The [ModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430850.pubmethod(en-us,PandP.50).gif "Public method")
[ModuleInitializer](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.)
Initializes a new instance of [ModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer).

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430850.protmethod(en-us,PandP.50).gif "Protected method")
[CreateModule(String)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.createmodule(system.string))
Uses the container to resolve a new [IModule](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule) by specifying its [Type](http://msdn2.microsoft.com/en-us/library/42892f65).

![](https://msdn.microsoft.com/en-us/Gg430850.protmethod(en-us,PandP.50).gif "Protected method")
[CreateModule(ModuleInfo)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.createmodule(microsoft.practices.prism.modularity.moduleinfo))
Uses the container to resolve a new [IModule](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule) by specifying its [Type](http://msdn2.microsoft.com/en-us/library/42892f65).

![](https://msdn.microsoft.com/en-us/Gg430850.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430850.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430850.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430850.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430850.pubmethod(en-us,PandP.50).gif "Public method")
[HandleModuleInitializationError](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.handlemoduleinitializationerror(microsoft.practices.prism.modularity.moduleinfo%2csystem.string%2csystem.exception))
Handles any exception occurred in the module Initialization process, logs the error using the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) and throws a [ModuleInitializeException](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializeexception). This method can be overridden to provide a different behavior.

![](https://msdn.microsoft.com/en-us/Gg430850.pubmethod(en-us,PandP.50).gif "Public method")
[Initialize](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.initialize(microsoft.practices.prism.modularity.moduleinfo))
Initializes the specified module.

![](https://msdn.microsoft.com/en-us/Gg430850.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430850.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleInitializer Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)