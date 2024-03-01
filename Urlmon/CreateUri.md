## CreateUri

```
[DllImport("urlmon.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int CreateUri(
   [MarshalAs(UnmanagedType.LPWStr)] string uri,
   uint flags,
   int dwReserved,
   out IntPtr uri
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-createuri)
