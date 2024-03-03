## OleRegEnumFormatEtc

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleRegEnumFormatEtc(
   ref Guid clsid,
   uint dwDirection,
   out IEnumFORMATETC ppenum
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-oleregenumformatetc)
