## ConvertSecurityDescriptorToStringSecurityDescriptor

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertSecurityDescriptorToStringSecurityDescriptor(
   IntPtr SecurityDescriptor,
   uint RequestedStringSDRevision,
   uint SecurityInformation,
   out IntPtr StringSecurityDescriptor,
   out uint StringSecurityDescriptorLen
);
```

[Microsoft documentation](TODO)
