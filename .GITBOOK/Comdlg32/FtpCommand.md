## FtpCommand

```csharp
[DllImport("Comdlg32.dll", SetLastError = true)]
public static extern bool FtpCommand(
   IntPtr hConnect,
   [MarshalAs(UnmanagedType.Bool)] bool fExpectResponse,
   uint dwFlags,
   [MarshalAs(UnmanagedType.LPStr)] string lpszCommand,
   IntPtr dwReserved,
   out IntPtr phInternet
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftpcommanda)
