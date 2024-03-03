## IsProcessCritical

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern bool IsProcessCritical(
   IntPtr hProcess,
   out bool Critical
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-isprocesscritical)
