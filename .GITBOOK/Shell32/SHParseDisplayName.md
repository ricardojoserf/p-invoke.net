## SHParseDisplayName

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHParseDisplayName(
   string pszName,
   IntPtr pbc,
   out IntPtr ppidl,
   SFGAO sfgaoIn,
   out SFGAO psfgaoOut
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shparsedisplayname)
