# IModel.Copy&lt;T&gt; method

Create a model [`structure`](../IStructure.md) by deep copying the given *source*.

```csharp
public T Copy<T>(T source)
    where T : class, IStructure
```

| parameter | description |
| --- | --- |
| T | Type of the structure to copy. |

## Return Value

Copy of the *source*. It is not attached to a model.

## See Also

* interface [IStructure](../IStructure.md)
* interface [IModel](../IModel.md)
* namespace [Mendix.StudioPro.ExtensionsAPI.Model](../../Mendix.StudioPro.ExtensionsAPI.md)

<!-- DO NOT EDIT: generated by xmldocmd for Mendix.StudioPro.ExtensionsAPI.dll -->