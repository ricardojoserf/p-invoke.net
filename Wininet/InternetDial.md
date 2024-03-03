## InternetDial

```csharp
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern int InternetDial(
   IntPtr hwndParent,
   string lpszConnectoid,
   uint dwFlags,
   ref int lpdwConnection,
   uint dwReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetdiala)
