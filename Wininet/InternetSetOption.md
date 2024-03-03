## InternetSetOption

```csharp
[DllImport("wininet.dll", SetLastError = true)]
public static extern bool InternetSetOption(
   IntPtr hInternet,
   uint dwOption,
   IntPtr lpBuffer,
   uint dwBufferLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetsetoptiona)
