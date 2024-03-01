## CryptUpdateProtectedState

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptUpdateProtectedState(
   ref IntPtr pOldSid,
   ref IntPtr pOldProtectData,
   ref IntPtr pNewSid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/dpapi/nf-dpapi-cryptupdateprotectedstate)
