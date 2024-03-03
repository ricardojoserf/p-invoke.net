## NtResumeProcess

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtResumeProcess(
   IntPtr ProcessHandle
);
```

