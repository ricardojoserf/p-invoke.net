## LoadTypeLibEx

```csharp
[DllImport("oleaut32.dll", CharSet = CharSet.Unicode, PreserveSig = false)]
public static extern void LoadTypeLibEx(
   string szFile,
   int regkind,
   out ITypeLib pptlib
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/oleauto/nf-oleauto-loadtypelibex)
