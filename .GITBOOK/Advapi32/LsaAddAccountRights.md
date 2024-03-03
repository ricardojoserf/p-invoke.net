## LsaAddAccountRights

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LsaAddAccountRights(
   IntPtr PolicyHandle,
   IntPtr AccountSid,
   LSA_UNICODE_STRING[] UserRights,
   uint CountOfRights
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaaddaccountrights)
