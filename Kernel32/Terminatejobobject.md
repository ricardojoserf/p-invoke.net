## Terminatejobobject

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool TerminateJobObject(
   IntPtr hJob,
   uint uExitCode
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi/nf-jobapi-terminatejobobject)
