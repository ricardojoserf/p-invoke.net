## FtpDeleteFile

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FtpDeleteFile(
   IntPtr hConnect,
   string lpszFileName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftpdeletefilea)
