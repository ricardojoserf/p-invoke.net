## LoadTypeLib

```csharp
[DllImport("oleaut32.dll", CharSet = CharSet.Unicode, PreserveSig = false)]
public static extern void LoadTypeLib(
   string szFile,
   out ITypeLib pptlib
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/oleauto/nf-oleauto-loadtypelib)
