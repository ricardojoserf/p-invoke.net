## CoQueryAuthenticationServices

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoQueryAuthenticationServices(
   out uint pcAuthSvc,
   out SOLE_AUTHENTICATION_SERVICE[] asAuthSvc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coqueryauthenticationservices)
