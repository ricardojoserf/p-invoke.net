## FtpPutFile

```csharp
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FtpPutFile(
   IntPtr hConnect,
   string lpszLocalFile,
   string lpszNewRemoteFile,
   uint dwFlags,
   IntPtr dwContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftpputfilea)
