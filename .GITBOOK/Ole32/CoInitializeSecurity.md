## CoInitializeSecurity

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoInitializeSecurity(
   IntPtr pSecDesc,
   int cAuthSvc,
   SOLE_AUTHENTICATION_SERVICE[] asAuthSvc,
   IntPtr pReserved1,
   RPC_C_AUTHN_LEVEL dwAuthnLevel,
   RPC_C_IMP_LEVEL dwImpLevel,
   IntPtr pAuthList,
   EOLE_AUTHENTICATION_CAPABILITIES dwCapabilities,
   IntPtr pReserved3
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coinitializesecurity)
