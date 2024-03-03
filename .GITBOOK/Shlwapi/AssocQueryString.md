## AssocQueryString

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int AssocQueryString(
   ASSOCF flags,
   ASSOCSTR str,
   [MarshalAs(UnmanagedType.LPWStr)] string pszAssoc,
   [MarshalAs(UnmanagedType.LPWStr)] string pszExtra,
   [MarshalAs(UnmanagedType.LPWStr)] StringBuilder pszOut,
   ref uint pcchOut
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-assocquerystringw)
