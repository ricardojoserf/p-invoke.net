## ConvertStringSecurityDescriptorToSecurityDescriptor

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertStringSecurityDescriptorToSecurityDescriptor(
   string StringSecurityDescriptor,
   uint StringSDRevision,
   out IntPtr SecurityDescriptor,
   out uint SecurityDescriptorSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertstringsecuritydescriptortosecuritydescriptora)
