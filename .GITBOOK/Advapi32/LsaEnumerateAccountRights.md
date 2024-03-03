## LsaEnumerateAccountRights

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LsaEnumerateAccountRights(
   IntPtr PolicyHandle,
   IntPtr AccountSid,
   out IntPtr UserRights,
   out uint CountOfRights
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenumerateaccountrights)
