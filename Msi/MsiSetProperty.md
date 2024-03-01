## MsiSetProperty

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiSetProperty(
   IntPtr hInstall,
   [MarshalAs(UnmanagedType.LPTStr)] string szName,
   [MarshalAs(UnmanagedType.LPTStr)] string szValue
);
```

Microsoft documentation: (TODO)
