## RegisterTypeLib

```
[DllImport("oleaut32.dll", CharSet = CharSet.Unicode, PreserveSig = false)]
public static extern void RegisterTypeLib(
   ITypeLib ptlib,
   string szFullPath,
   string szHelpDir
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/oleauto/nf-oleauto-registertypelib)
