## SHLoadIndirectString

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int SHLoadIndirectString(
   [MarshalAs(UnmanagedType.LPWStr)] string pszSource,
   StringBuilder pszOutBuf,
   uint cchOutBuf,
   IntPtr ppvReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-shloadindirectstring)
