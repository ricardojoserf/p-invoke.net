## CoQueryProxyBlanket

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoQueryProxyBlanket(
   IUnknown pProxy,
   out IntPtr pAuthnSvc,
   out IntPtr pAuthzSvc,
   [MarshalAs(UnmanagedType.LPWStr)] out string pServerPrincName,
   out IntPtr pAuthnLevel,
   out IntPtr pImpLevel,
   out IntPtr pPrivs,
   out uint pCapabilities
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coqueryproxyblanket)
