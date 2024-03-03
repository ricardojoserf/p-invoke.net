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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msigetpropertya)
