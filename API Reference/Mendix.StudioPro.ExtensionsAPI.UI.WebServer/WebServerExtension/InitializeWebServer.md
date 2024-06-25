# WebServerExtension.InitializeWebServer method

This method is called once to allow this extension to configure the built-in web server of Studio Pro. Use this method to add routes to the web server.

```csharp
public abstract void InitializeWebServer(IWebServer webServer)
```

| parameter | description |
| --- | --- |
| webServer | An object representing the internal web server of Studio Pro. |

## Remarks

This method is called at most once after the extension is loaded.

## See Also

* interface [IWebServer](../IWebServer.md)
* class [WebServerExtension](../WebServerExtension.md)
* namespace [Mendix.StudioPro.ExtensionsAPI.UI.WebServer](../../Mendix.StudioPro.ExtensionsAPI.md)

<!-- DO NOT EDIT: generated by xmldocmd for Mendix.StudioPro.ExtensionsAPI.dll -->