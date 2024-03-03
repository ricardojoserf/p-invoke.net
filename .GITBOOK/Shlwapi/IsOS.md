## IsOS

```csharp
[DllImport("shlwapi.dll")]
public static extern bool IsOS(
   OSVERSIONINFOEX osvi,
   OSFLAVOR dwTypeMask
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-isos)
