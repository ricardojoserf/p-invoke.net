## GetExitCodeProcess

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool GetExitCodeProcess(
   IntPtr hProcess,
   out uint lpExitCode
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getexitcodeprocess)
