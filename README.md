## MondoCore

<br/>
This organization is a container for various repositories that provide NuGet packages for common use needs of .Net applications, especially Azure based cloud applications.

<br/>

***
### Common/Generic Libraries

> These are non-Azure libraries that provide various functionalities.

#### <a href="https://github.com/MondoCore/MondoCore.Collections">MondoCore.Collections</a>

> A set of collections and collection related extensions.

#### <a href="https://github.com/MondoCore/MondoCore.Common">MondoCore.Common</a>

> Provides useful utility classes, extensions and interfaces.

#### <a href="https://github.com/MondoCore/MondoCore.Data">MondoCore.Data</a>

> Provides database related interfaces.

#### <a href="https://github.com/MondoCore/MondoCore.Log">MondoCore.Log</a>

> Provides a modern logging library. Must be used with a provider such as MondoCore.Azure.ApplicationInsights.

#### <a href="https://github.com/MondoCore/MondoCore.MongoDB">MondoCore.MongoDB</a>

> Wraps around the .Net Mongo client library and implements the interfaces from the MondoCore.Data library.

#### <a href="https://github.com/MondoCore/MondoCore.Rest">MondoCore.Rest</a>

> Classes and interfaces for calling Rest apis.

<br/>

***
### Azure Libraries

> These are wrappers around Azure client libraries. They insulate against changes in the Microsoft client libraries and implement one of the interfaces defined in other MondoCore libraries to allow easy mocking or substitution.

#### <a href="https://github.com/MondoCore/MondoCore.Azure.ApplicationInsights">MondoCore.Azure.ApplicationInsights</a>

> Wraps around the Microsoft ApplicationInsights client library. Implements the ILog interface from the MondoCore.Log library. Not meant to be used directly. See the repo documentation for usage.


#### <a href="https://github.com/MondoCore/MondoCore.Azure.Cosmos">MondoCore.Azure.Cosmos</a>

> Wraps around the Microsoft Cosmos client library. Implements the ILog interface from the [MondoCore.Data](https://github.com/MondoCore/MondoCore.Data) library.


#### <a href="https://github.com/MondoCore/MondoCore.Azure.Configuration">MondoCore.Azure.Configuration</a>

> Wraps around the Microsoft Appliation Config client library.

