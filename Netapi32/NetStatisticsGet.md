## NetStatisticsGet

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetStatisticsGet(
   string ServerName,
   string Service,
   uint Level,
   uint Options,
   out IntPtr Buffer
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmstats/nf-lmstats-netstatisticsget)
