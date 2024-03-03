## FtpSetCurrentDirectory

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FtpSetCurrentDirectory(
   IntPtr hConnect,
   string lpszDirectory
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftpsetcurrentdirectorya)
