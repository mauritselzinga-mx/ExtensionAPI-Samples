# IDomainModelService.GetAssociationsBetweenEntities method

It returns all [`EntityAssociation`](../../Mendix.StudioPro.ExtensionsAPI.Model.DomainModels/EntityAssociation.md) in the current app between two [`IEntity`](../../Mendix.StudioPro.ExtensionsAPI.Model.DomainModels/IEntity.md) objects when one entity is the parent and the other is the child.

```csharp
public IList<EntityAssociation> GetAssociationsBetweenEntities(IModel currentApp, IEntity parent, 
    IEntity child)
```

| parameter | description |
| --- | --- |
| currentApp | The current app. |
| parent | The [`IEntity`](../../Mendix.StudioPro.ExtensionsAPI.Model.DomainModels/IEntity.md) which is the parent of the [`IAssociation`](../../Mendix.StudioPro.ExtensionsAPI.Model.DomainModels/IAssociation.md). |
| child | The [`IEntity`](../../Mendix.StudioPro.ExtensionsAPI.Model.DomainModels/IEntity.md) which is the child of the [`IAssociation`](../../Mendix.StudioPro.ExtensionsAPI.Model.DomainModels/IAssociation.md). |

## Return Value

List of [`EntityAssociation`](../../Mendix.StudioPro.ExtensionsAPI.Model.DomainModels/EntityAssociation.md)

## See Also

* record [EntityAssociation](../../Mendix.StudioPro.ExtensionsAPI.Model.DomainModels/EntityAssociation.md)
* interface [IModel](../../Mendix.StudioPro.ExtensionsAPI.Model/IModel.md)
* interface [IEntity](../../Mendix.StudioPro.ExtensionsAPI.Model.DomainModels/IEntity.md)
* interface [IDomainModelService](../IDomainModelService.md)
* namespace [Mendix.StudioPro.ExtensionsAPI.Services](../../Mendix.StudioPro.ExtensionsAPI.md)

<!-- DO NOT EDIT: generated by xmldocmd for Mendix.StudioPro.ExtensionsAPI.dll -->