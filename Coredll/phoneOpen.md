## phoneOpen

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern int phoneOpen(
   IntPtr hLine,
   uint dwAddressID,
   out IntPtr hPhone,
   int dwAPIVersion,
   int dwExtVersion,
   int dwCallbackInstance,
   int dwPrivileges
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/tapi/nf-tapi-phoneopen)
