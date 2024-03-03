## LookupPrivilegeDisplayName

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LookupPrivilegeDisplayName(
   string lpSystemName,
   string lpName,
   StringBuilder lpDisplayName,
   ref uint cchDisplayName,
   out uint lpLanguageId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegedisplaynamea)
