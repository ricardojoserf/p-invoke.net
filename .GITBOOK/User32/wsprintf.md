## wsprintf

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern int wsprintf(
   StringBuilder lpOut,
   string lpFmt,
   params object[] args
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-wsprintfa)
