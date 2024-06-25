# IDialogService.CloseDialog method

Closes a modal dialog previously opened from the [`ShowDialog`](./ShowDialog.md) method. It returns errors if trying to close a dialog that was not previously opened or that has already been closed.

```csharp
public void CloseDialog(ModalDialogViewModelBase dialog)
```

## Exceptions

| exception | condition |
| --- | --- |
| Exception | *dialog* is null. |
| Exception | Thrown if the dialog was not initialized correctly. |

## See Also

* class [ModalDialogViewModelBase](../../Mendix.StudioPro.ExtensionsAPI.UI.Dialogs/ModalDialogViewModelBase.md)
* interface [IDialogService](../IDialogService.md)
* namespace [Mendix.StudioPro.ExtensionsAPI.UI.Services](../../Mendix.StudioPro.ExtensionsAPI.md)

<!-- DO NOT EDIT: generated by xmldocmd for Mendix.StudioPro.ExtensionsAPI.dll -->