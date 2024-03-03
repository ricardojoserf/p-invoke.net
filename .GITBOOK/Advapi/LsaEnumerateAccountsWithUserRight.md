## LsaEnumerateAccountsWithUserRight

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LsaEnumerateAccountsWithUserRight(
   IntPtr PolicyHandle,
   LSA_UNICODE_STRING UserRight,
   out IntPtr EnumerationBuffer,
   out uint CountReturned
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenumerateaccountswithuserright)
