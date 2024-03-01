## SHParseDisplayName

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHParseDisplayName(
   string pszName,
   IntPtr pbc,
   out IntPtr ppidl,
   SFGAO sfgaoIn,
   out SFGAO psfgaoOut
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shobjidl_core/nf-shobjidl_core-shparsedisplayname)
