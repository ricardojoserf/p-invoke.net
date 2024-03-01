## CallNtPowerInformation

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern int CallNtPowerInformation(
   int InformationLevel,
   IntPtr lpInputBuffer,
   uint nInputBufferSize,
   IntPtr lpOutputBuffer,
   uint nOutputBufferSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-callntpowerinformation)
