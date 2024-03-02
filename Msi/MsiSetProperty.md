## MsiSetProperty

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiSetProperty(
   IntPtr hInstall,
   [MarshalAs(UnmanagedType.LPTStr)] string szName,
   [MarshalAs(UnmanagedType.LPTStr)] string szValue
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msisetpropertya)
