## LsaOpenPolicy

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LsaOpenPolicy(
   ref LSA_UNICODE_STRING SystemName,
   ref LSA_OBJECT_ATTRIBUTES ObjectAttributes,
   uint DesiredAccess,
   out IntPtr PolicyHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaopenpolicy)
