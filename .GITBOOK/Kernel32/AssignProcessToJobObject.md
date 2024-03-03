## AssignProcessToJobObject

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AssignProcessToJobObject(
   IntPtr hJob,
   IntPtr hProcess
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/jobapi2/nf-jobapi2-assignprocesstojobobject)
