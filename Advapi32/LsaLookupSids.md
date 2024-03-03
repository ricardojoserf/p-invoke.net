## LsaLookupSids

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LsaLookupSids(
   IntPtr PolicyHandle,
   uint Count,
   IntPtr Sids,
   out IntPtr ReferencedDomains,
   out IntPtr Names
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupsids)
