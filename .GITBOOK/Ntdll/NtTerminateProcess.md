## NtTerminateProcess

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtTerminateProcess(
   IntPtr ProcessHandle,
   int ExitStatus
);
```

Microsoft documentation: [Link](https://ntdoc.m417z.com/ntterminateprocess)
