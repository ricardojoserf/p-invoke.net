## UrlMkGetSessionOption

```csharp
[DllImport("urlmon.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int UrlMkGetSessionOption(
   int dwOption,
   IntPtr pBuffer,
   int dwBufferLength,
   ref int pdwBufferLength,
   int dwReserved
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/ms775124(v=vs.85))
