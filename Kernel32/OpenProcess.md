## OpenProcess

```csharp
[DllImport("kernel32.dll", SetLastError = true)]
public static extern IntPtr OpenProcess(
   uint dwDesiredAccess,
   bool bInheritHandle,
   uint dwProcessId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-openprocess)
