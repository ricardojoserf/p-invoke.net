## SetSecurityDescriptorDacl

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetSecurityDescriptorDacl(
   IntPtr pSecurityDescriptor,
   [MarshalAs(UnmanagedType.Bool)] bool bDaclPresent,
   IntPtr pDacl,
   [MarshalAs(UnmanagedType.Bool)] bool bDaclDefaulted
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setsecuritydescriptordacl)
