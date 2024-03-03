## CoSetProxyBlanket

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoSetProxyBlanket(
   IUnknown pProxy,
   uint dwAuthnSvc,
   uint dwAuthzSvc,
   [MarshalAs(UnmanagedType.LPWStr)] string pServerPrincName,
   uint dwAuthnLevel,
   uint dwImpLevel,
   IntPtr pAuthInfo,
   uint dwCapabilities
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cosetproxyblanket)
