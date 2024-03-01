## MsiViewFetch

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiViewFetch(
   IntPtr hView,
   out IntPtr hRecord
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msiviewfetch)
