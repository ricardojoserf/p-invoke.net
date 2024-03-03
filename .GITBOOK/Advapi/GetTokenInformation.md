## GetTokenInformation

```
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool GetTokenInformation(
   IntPtr TokenHandle,
   TOKEN_INFORMATION_CLASS TokenInformationClass,
   IntPtr TokenInformation,
   uint TokenInformationLength,
   out uint ReturnLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-gettokeninformation)
