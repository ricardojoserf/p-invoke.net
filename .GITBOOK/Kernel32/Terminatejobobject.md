## Terminatejobobject

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool TerminateJobObject(IntPtr hJob,
   uint uExitCode
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/jobapi2/nf-jobapi2-terminatejobobject)
