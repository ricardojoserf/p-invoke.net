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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/ms775098(v=vs.85))
