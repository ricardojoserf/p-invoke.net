## AssocCreate

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int AssocCreate(
   Guid clsid,
   ref Guid riid,
   out IntPtr ppv
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-assoccreate)
