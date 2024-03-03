## SHIsFileAvailableOffline

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHIsFileAvailableOffline(
   IntPtr pwszPath,
   uint pdwStatus
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shisfileavailableoffline)
