# Azure PowerShell AutoRest Configuration

> Values
``` yaml
azure: true
powershell: true
branch: azsfabricgen
repo: https://github.com/seyadava/azure-rest-api-specs/blob/$(branch)
```

> Names
``` yaml
prefix: Azs
subject-prefix: Fabric
module-name: $(prefix).$(service-name)
namespace: Microsoft.Azure.PowerShell.Cmdlets.$(service-name)
```

> Folders
``` yaml
clear-output-folder: true
output-folder: .
```

> Directives
``` yaml
directive:
  - where:
      subject: Operation
    hide: true
```