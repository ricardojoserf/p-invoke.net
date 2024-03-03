## FtpCommand

```csharp
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FtpCommand(
   IntPtr hConnect,
   bool fExpectResponse,
   uint dwFlags,
   string lpszCommand,
   IntPtr dwContext,
   ref IntPtr phFtpCommand
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftpcommanda)
