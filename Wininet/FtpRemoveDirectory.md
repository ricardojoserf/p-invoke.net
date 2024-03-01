## FtpRemoveDirectory

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FtpRemoveDirectory(
   IntPtr hConnect,
   string lpszDirectory
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftpremovedirectorya)
