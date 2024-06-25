# IQualifiedName&lt;T&gt; interface

Represents a [by-name reference](https://docs.mendix.com/apidocs-mxsdk/mxsdk/understanding-the-metamodel#3-1-references) to an object (element or unit) or type *T* in metamodel. The reference can be resolved to retrieve the object it is referencing.

```csharp
public interface IQualifiedName<out T> : IQualifiedName
    where T : class
```

| parameter | description |
| --- | --- |
| T | Type of the referenced object. |

## Members

| name | description |
| --- | --- |
| [Resolve](IQualifiedName-1/Resolve.md)() | Retrieve the referenced object. |

## Remarks

Apps can contain invalid references, for example references to objects removed from the app. Such references are called invalid and they cannot be resolved even if an object they point to still exists in Studio Pro's memory.

## See Also

* interface [IQualifiedName](./IQualifiedName.md)
* namespace [Mendix.StudioPro.ExtensionsAPI.Model](../Mendix.StudioPro.ExtensionsAPI.md)

<!-- DO NOT EDIT: generated by xmldocmd for Mendix.StudioPro.ExtensionsAPI.dll -->