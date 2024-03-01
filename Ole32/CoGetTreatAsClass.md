## CoGetTreatAsClass

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetTreatAsClass(
   ref Guid clsidOld,
   out Guid pClsidNew
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogettreatasclass)
