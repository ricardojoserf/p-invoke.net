## InternetCrackUrl

```csharp
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool InternetCrackUrl(
   string lpszUrl,
   uint dwUrlLength,
   uint dwFlags,
   ref URL_COMPONENTS lpUrlComponents
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetcrackurla)
