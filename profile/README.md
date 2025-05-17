## MondoCore

<br/>
This organization is a container for various repositories that provide NuGet packages for common use needs of .Net applications, especially Azure based cloud applications.

<br/>
<br/>

### Table of Contents
- [Common/Generic](#commongeneric)
    - [MondoCore.Collections](#collections)
    - [MondoCore.Common](#common)
    - [MondoCore.Log](#log)
    - [MondoCore.Rest](#rest)
    - [MondoCore.Security](#security)
- [Database](#database)
    - [MondoCore.Azure.Cosmos](#cosmos)
    - [MondoCore.Data](#data)
    - [MondoCore.MongoDB](#mongo)
- [Azure](#azure)
    - [MondoCore.Azure.ApplicationInsights](#appinsights)
    - [MondoCore.Azure.Configuration](#config)
    - [MondoCore.Azure.Cosmos](#cosmos)
    - [MondoCore.Azure.Keyvault](#keyvault)

<br/>

***
<a id="commongeneric" />

### Common/Generic Libraries

> These are non-Azure libraries that provide various functionalities.

<a id="collections" />

#### <a href="https://github.com/MondoCore/MondoCore.Collections">MondoCore.Collections</a>

> A set of collections and collection related extensions.

<a id="common" />

#### <a href="https://github.com/MondoCore/MondoCore.Common">MondoCore.Common</a>

> Provides useful utility classes, extensions and interfaces.

<a id="log" />

#### <a href="https://github.com/MondoCore/MondoCore.Log">MondoCore.Log</a>

> Provides a modern logging library. Must be used with a provider such as MondoCore.Azure.ApplicationInsights.

<a id="rest" />

#### <a href="https://github.com/MondoCore/MondoCore.Rest">MondoCore.Rest</a>

> Classes and interfaces for calling Rest apis.

<a id="security" />

#### <a href="https://github.com/MondoCore/MondoCore.Security">MondoCore.Security</a>

> Classes and interfaces for encryption, password hashing and totp generation.

<br/>

***
<a id="database" />

### Database Libraries

> These are database related classes and interfaces.

<a id="data" />

#### <a href="https://github.com/MondoCore/MondoCore.Data">MondoCore.Data</a>

> Provides database related interfaces.

<a id="mongo" />

#### <a href="https://github.com/MondoCore/MondoCore.MongoDB">MondoCore.MongoDB</a>

> Wraps around the .Net Mongo client library and implements the interfaces from the MondoCore.Data library.


***
<a id="azure" />

### Azure Libraries

> These are wrappers around Azure client libraries. They insulate against changes in the Microsoft client libraries and implement one of the interfaces defined in other MondoCore libraries to allow easy mocking or substitution.

<a id="appinsights" />

#### <a href="https://github.com/MondoCore/MondoCore.Azure.ApplicationInsights">MondoCore.Azure.ApplicationInsights</a>

> Wraps around the Microsoft ApplicationInsights client library. Implements the ILog interface from the MondoCore.Log library. Not meant to be used directly. See the repo documentation for usage.

<a id="cosmos" />

#### <a href="https://github.com/MondoCore/MondoCore.Azure.Cosmos">MondoCore.Azure.Cosmos</a>

> Wraps around the Microsoft Cosmos client library. Implements the IDatabase interface from the [MondoCore.Data](https://github.com/MondoCore/MondoCore.Data) library.

<a id="config" />

#### <a href="https://github.com/MondoCore/MondoCore.Azure.Configuration">MondoCore.Azure.Configuration</a>

> Wraps around the Microsoft Application Config client library.

<a id="keyvault" />

#### <a href="https://github.com/MondoCore/MondoCore.Azure.Keyvault">MondoCore.Azure.Keyvault</a>

> Provides a Keyvault implementation of IBlobStore

