## IsProcessInJob

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool IsProcessInJob(
   IntPtr ProcessHandle,
   IntPtr JobHandle,
   out bool Result
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi/nf-jobapi-isprocessinjob)
