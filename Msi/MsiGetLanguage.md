## MsiGetLanguage

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetLanguage(
   [MarshalAs(UnmanagedType.LPTStr)] string szProduct,
   [MarshalAs(UnmanagedType.LPTStr)] string szLang,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpLangBuf,
   ref int pcchLangBuf
);
```

Microsoft documentation: (TODO)
