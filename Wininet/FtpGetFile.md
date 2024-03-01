## FtpGetFile

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FtpGetFile(
   IntPtr hConnect,
   string lpszRemoteFile,
   string lpszNewFile,
   bool fFailIfExists,
   uint dwFlagsAndAttributes,
   uint dwFlags,
   IntPtr dwContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftpgetfilea)
