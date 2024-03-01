## MsiGetShortcutTarget

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetShortcutTarget(
   [MarshalAs(
   UnmanagedType.LPTStr)] string szShortcutTarget,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder szProductCode,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder szFeatureId,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder szComponentCode
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msigetshortcuttargetw)
