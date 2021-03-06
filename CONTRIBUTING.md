# Contributing

This project has adopted the [Microsoft Open Source Code of
Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct
FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com)
with any additional questions or comments.

## Building

### Prerequisites

* [.NET Core SDK](https://dotnet.microsoft.com/download/dotnet-core/2.2) with the version matching our [global.json](global.json) file. The version you install must be at least the version specified in the global.json file, and must be within the same hundreds version for the 3rd integer: x.y.Czz (x.y.C must match, and zz must be at least as high).
* Optional: [Visual Studio 2019](https://www.visualstudio.com/)

### Build steps

This project can be built with the follow commands from a Visual Studio Developer Command Prompt,
assuming the working directory is the root of this repository:

```ps1
dotnet build src
```

This solution can also be built from within Visual Studio 2019.

## Pull requests

We are not yet accepting external pull requests for this repository.

We hope to soon.
