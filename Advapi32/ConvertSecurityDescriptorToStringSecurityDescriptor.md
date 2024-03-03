## ConvertSecurityDescriptorToStringSecurityDescriptor

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertSecurityDescriptorToStringSecurityDescriptor(
   IntPtr SecurityDescriptor,
   uint RequestedStringSDRevision,
   uint SecurityInformation,
   out IntPtr StringSecurityDescriptor,
   out uint StringSecurityDescriptorLen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertsecuritydescriptortostringsecuritydescriptora)
