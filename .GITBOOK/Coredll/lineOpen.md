## lineOpen

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern int lineOpen(
   IntPtr hLineApp,
   int dwDeviceID,
   out IntPtr phLine,
   int dwAPIVersion,
   int dwExtVersion,
   int dwCallbackInstance,
   int dwPrivileges,
   int dwMediaModes,
   ref LINECALLPARAMS lpCallParams
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/tapi/nf-tapi-lineopenw)
