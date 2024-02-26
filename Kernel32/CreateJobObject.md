## CreateJobObject

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeJobHandle CreateJobObject(IntPtr lpJobAttributes, string lpName);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi2/nf-jobapi2-createjobobjectw)
