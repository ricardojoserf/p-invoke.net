## WTSEnumerateProcesses

```csharp
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSEnumerateProcesses(
   IntPtr hServer,
   int Reserved,
   int Version,
   ref IntPtr ppProcessInfo,
   ref int pCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsenumerateprocessesa)
