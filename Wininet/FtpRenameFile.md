## FtpRenameFile

```csharp
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FtpRenameFile(
   IntPtr hConnect,
   string lpszExisting,
   string lpszNew
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-ftprenamefilea)
