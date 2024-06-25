# ITransaction interface

Transaction grouping the changes in the app model.

```csharp
public interface ITransaction : IDisposable
```

## Members

| name | description |
| --- | --- |
| [Commit](ITransaction/Commit.md)() | Commit the transaction. That indicates that an atomic set of changes is completed and: saves all affected documents that are not currently being edited by a user; adds an undo item for the documents that are edited. |
| [Rollback](ITransaction/Rollback.md)() | Roll back the transaction. That is, undo all changes done during it. |

## Remarks

Transactions provide a way to group changes together and to give a user-friendly name for these changes (visible in Edit -&gt; Undo menu). Transactions must be committed or rolled back where the latter one can be achieved by explicitly calling [`Rollback`](./ITransaction/Rollback.md) or by implicit call to Dispose e.g. due to an exception being thrown. Committed transaction can later be reverted by a user using undo. Changes done within a transaction are not isolated, that is other parts of Studio Pro code, including editors, react to them even before [`Commit`](./ITransaction/Commit.md) is called. It is not recommended to have transactions active while a user can interact with Studio Pro screens different from the one you control.

## Examples

Transactions can be created using [`StartTransaction`](./IModel/StartTransaction.md).

## See Also

* namespace [Mendix.StudioPro.ExtensionsAPI.Model](../Mendix.StudioPro.ExtensionsAPI.md)

<!-- DO NOT EDIT: generated by xmldocmd for Mendix.StudioPro.ExtensionsAPI.dll -->