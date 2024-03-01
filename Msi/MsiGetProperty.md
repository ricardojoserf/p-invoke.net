## MsiGetProperty

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetProperty(
   IntPtr hInstall,
   [MarshalAs(UnmanagedType.LPTStr)] string szName,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder szValueBuf,
   ref int pcchValueBuf
);
```

[Microsoft documentation](TODO)
