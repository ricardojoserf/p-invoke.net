## CoTreatAsClass

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoTreatAsClass(
   ref Guid clsidOld,
   ref Guid clsidNew
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cotreatasclass)
