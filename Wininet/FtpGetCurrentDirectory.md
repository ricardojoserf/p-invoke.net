## FtpGetCurrentDirectory

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FtpGetCurrentDirectory(
   IntPtr hConnect,
   StringBuilder lpszCurrentDirectory,
   ref uint lpdwCurrentDirectory
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftpgetcurrentdirectorya)
