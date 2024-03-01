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

Microsoft documentation: (TODO)
