## MondoCore

<br/>
This organization is a container for various repositories that provide NuGet packages for common use needs of .Net applications, especially Azure based cloud applications.


### Azure Libraries

These are wrappers around Azure client libraries. They insulate against changes in the Microsoft client libraries and implement one of the interfaces defined in other MondoCore libraries to allow easy mocking or substitution.

#### <a href="https://github.com/MondoCore/MondoCore.Azure.ApplicationInsights">MondoCore.Azure.ApplicationInsights</a>

Wraps around the Microsoft ApplicationInsights client library. Implements the ILog interface from the MondoCore.Log library. Not meant to be used directly. See the repo documentation for usage.