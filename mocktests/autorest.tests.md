# Generated test code configuration

Run `dotnet build /t:GenerateTest` to generate test code.

``` yaml
require:
  - ../src/autorest.md
clear-output-folder: true
skip-csproj: true
output-folder: $(this-folder)/Generated
namespace: Azure.ResourceManager.AgriFood
```
