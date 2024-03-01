## ConvertSidToStringSid

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConvertSidToStringSid(
   IntPtr Sid,
   out IntPtr StringSid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-convertsidtostringsida)
