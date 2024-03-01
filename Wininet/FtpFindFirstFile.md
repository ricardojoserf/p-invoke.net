## FtpFindFirstFile

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern IntPtr FtpFindFirstFile(
   IntPtr hConnect,
   string lpszSearchFile,
   ref WIN32_FIND_DATA lpFindFileData,
   uint dwFlags,
   IntPtr dwContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftpfindfirstfilea)
