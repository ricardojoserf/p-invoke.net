## DsGetSiteName

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint DsGetSiteName(
   string ComputerName,
   out IntPtr SiteName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dsgetdc/nf-dsgetdc-dsgetsitenamew)
