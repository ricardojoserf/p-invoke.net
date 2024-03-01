## LsaStorePrivateData

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LsaStorePrivateData(
   IntPtr PolicyHandle,
   ref LSA_UNICODE_STRING KeyName,
   IntPtr PrivateData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsastoreprivatedata)
