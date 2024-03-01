## URLDownloadToFile

```
[DllImport("urlmon.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int URLDownloadToFile(
   IntPtr pCaller,
   [MarshalAs(UnmanagedType.LPWStr)] string szURL,
   [MarshalAs(UnmanagedType.LPWStr)] string szFileName,
   int dwReserved,
   IntPtr lpfnCB
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/urlmon/nf-urlmon-urldownloadtofilew)
