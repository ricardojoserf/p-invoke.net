## RasHangUp

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RasHangUp(
   IntPtr hrasconn
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ras/nf-ras-rashangupa)
