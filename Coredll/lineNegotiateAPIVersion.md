## lineNegotiateAPIVersion

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern int lineNegotiateAPIVersion(
   IntPtr hLineApp,
   int dwDeviceID,
   int dwAPILowVersion,
   int dwAPIHighVersion,
   out int lpdwAPIVersion,
   ref LINEEXTENSIONID lpExtensionID
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tapi/nf-tapi-linenegotiateapiversion)
