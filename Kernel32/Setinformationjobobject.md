## Setinformationjobobject

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetInformationJobObject(IntPtr hJob,
   JOBOBJECTINFOCLASS JobObjectInfoClass,
   IntPtr lpJobObjectInfo,
   uint cbJobObjectInfoLength
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/jobapi2/nf-jobapi2-setinformationjobobject)
