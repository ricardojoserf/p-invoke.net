## MsiProvideAssembly

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiProvideAssembly(
   [MarshalAs(UnmanagedType.LPTStr)] string szAssemblyName,
   [MarshalAs(UnmanagedType.LPTStr)] string szAppContext,
   uint dwInstallMode,
   IntPtr hInstall,
   uint dwAssemblies,
   IntPtr lpAssemblyInformation
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msiprovideassemblyw)
