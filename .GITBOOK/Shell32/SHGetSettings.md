## SHGetSettings

```csharp
[DllImport("shell32.dll")]
public static extern bool SHGetSettings(
   ref SHFOLDERCUSTOMSETTINGS pscs,
   SHGSS dwMask
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shgetsettings)
