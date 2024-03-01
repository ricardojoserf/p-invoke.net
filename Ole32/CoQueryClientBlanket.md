## CoQueryClientBlanket

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoQueryClientBlanket(
   out IntPtr pAuthnSvc,
   out IntPtr pAuthzSvc,
   [MarshalAs(UnmanagedType.LPWStr)] out string pServerPrincName,
   out IntPtr pAuthnLevel,
   out IntPtr pImpLevel,
   out IntPtr pPrivs,
   out uint pCapabilities
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coqueryclientblanket)
