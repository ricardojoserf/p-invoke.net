## CallNtPowerInformation

```csharp
[DllImport("powrprof.dll", SetLastError = true)]
public static extern int CallNtPowerInformation(
   int InformationLevel,
   IntPtr lpInputBuffer,
   uint nInputBufferSize,
   IntPtr lpOutputBuffer,
   uint nOutputBufferSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/powerbase/nf-powerbase-callntpowerinformation)
