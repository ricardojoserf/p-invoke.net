## Setinformationjobobject

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetInformationJobObject(IntPtr hJob,
   JOBOBJECTINFOCLASS JobObjectInfoClass,
   IntPtr lpJobObjectInfo,
   uint cbJobObjectInfoLength
);
```

[Microsoft documentation](TODO)
