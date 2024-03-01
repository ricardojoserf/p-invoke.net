## Setinformationjobobject

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetInformationJobObject(
   IntPtr hJob,
   JOBOBJECTINFOCLASS JobObjectInfoClass,
   IntPtr lpJobObjectInfo,
   uint cbJobObjectInfoLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/jobapi/nf-jobapi-setinformationjobobject)
