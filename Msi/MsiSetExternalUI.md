## MsiSetExternalUI

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiSetExternalUI(
   MsiExternalUiCallback puiHandler,
   uint dwMessageFilter,
   IntPtr pvContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msisetexternaluiw)
