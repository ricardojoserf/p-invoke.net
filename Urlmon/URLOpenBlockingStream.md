## URLOpenBlockingStream

```
[DllImport("urlmon.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int URLOpenBlockingStream(
   IntPtr pCaller,
   [MarshalAs(
   UnmanagedType.LPWStr)] string szURL,
   out IntPtr ppStream,
   int dwReserved,
   IntPtr lpfnCB
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/urlmon/nf-urlmon-urlopenblockingstreamw)
