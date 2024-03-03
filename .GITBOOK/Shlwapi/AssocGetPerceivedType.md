## AssocGetPerceivedType

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int AssocGetPerceivedType(
   [MarshalAs(UnmanagedType.LPWStr)] string pszExt,
   out IntPtr ppszType
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-assocgetperceivedtype)
