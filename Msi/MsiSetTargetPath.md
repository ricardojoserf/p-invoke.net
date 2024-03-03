## MsiSetTargetPath

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiSetTargetPath(
   IntPtr hInstall,
   [MarshalAs(UnmanagedType.LPTStr)] string szFolder,
   [MarshalAs(UnmanagedType.LPTStr)] string szPath
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msisettargetpatha)
