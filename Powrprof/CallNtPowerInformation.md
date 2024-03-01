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

Microsoft documentation: (TODO)
