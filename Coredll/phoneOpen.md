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

[Microsoft documentation](TODO)
