# IVersionControlService.IsProjectVersionControlled method

Shows whether the app is controlled by a version control system, no matter private or hosted by Mendix

```csharp
public bool IsProjectVersionControlled(IModel app)
```

| parameter | description |
| --- | --- |
| app | Reference to the currently opened app |

## Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown if the provided path is invalid |

## See Also

* interface [IModel](../../Mendix.StudioPro.ExtensionsAPI.Model/IModel.md)
* interface [IVersionControlService](../IVersionControlService.md)
* namespace [Mendix.StudioPro.ExtensionsAPI.UI.Services](../../Mendix.StudioPro.ExtensionsAPI.md)

<!-- DO NOT EDIT: generated by xmldocmd for Mendix.StudioPro.ExtensionsAPI.dll -->