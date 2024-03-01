## ConvertStringSecurityDescriptorToSecurityDescriptor

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertStringSecurityDescriptorToSecurityDescriptor(
   string StringSecurityDescriptor,
   uint StringSDRevision,
   out IntPtr SecurityDescriptor,
   out uint SecurityDescriptorSize
);
```

[Microsoft documentation](TODO)
