## VariantChangeTypeEx

```
[DllImport("oleaut32.dll", SetLastError = true)]
public static extern int VariantChangeTypeEx(
   IntPtr pvargDest,
   IntPtr pvarSrc,
   uint lcid,
   ushort wFlags,
   ushort vt
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/oleauto/nf-oleauto-variantchangetypeex)
