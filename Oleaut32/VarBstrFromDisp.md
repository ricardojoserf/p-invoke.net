## VarBstrFromDisp

```
[DllImport("oleaut32.dll", SetLastError = true)]
public static extern int VarBstrFromDisp(
   IntPtr pdispIn,
   int lcid,
   uint dwFlags,
   out IntPtr pbstrOut
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/oleauto/nf-oleauto-varbstrfromdisp)
