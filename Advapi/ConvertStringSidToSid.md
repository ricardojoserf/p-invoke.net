## ConvertStringSidToSid

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertStringSidToSid(
   string StringSid,
   out IntPtr Sid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-convertstringsidtosida)
