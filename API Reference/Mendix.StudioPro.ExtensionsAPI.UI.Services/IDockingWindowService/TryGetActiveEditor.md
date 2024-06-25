# IDockingWindowService.TryGetActiveEditor method

Tries to get the model unit of the active editor tab.

```csharp
public bool TryGetActiveEditor(IModel model, out IAbstractUnit? unit)
```

| parameter | description |
| --- | --- |
| model | The app model. |
| unit | When this method returns, contains the model unit that is currently opened in an editor or an undefined value on failure. |

## Return Value

`true` if the active editor was successfully determined; otherwise, `false`.

## Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | When *model* is null. |
| InvalidOperationException | When there is no app open in Studio Pro. |

## See Also

* interface [IModel](../../Mendix.StudioPro.ExtensionsAPI.Model/IModel.md)
* interface [IAbstractUnit](../../Mendix.StudioPro.ExtensionsAPI.Model/IAbstractUnit.md)
* interface [IDockingWindowService](../IDockingWindowService.md)
* namespace [Mendix.StudioPro.ExtensionsAPI.UI.Services](../../Mendix.StudioPro.ExtensionsAPI.md)

<!-- DO NOT EDIT: generated by xmldocmd for Mendix.StudioPro.ExtensionsAPI.dll -->