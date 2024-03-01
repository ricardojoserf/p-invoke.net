## SetTokenInformation

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetTokenInformation(
   IntPtr TokenHandle,
   TOKEN_INFORMATION_CLASS TokenInformationClass,
   IntPtr TokenInformation,
   uint TokenInformationLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-settokeninformation)
