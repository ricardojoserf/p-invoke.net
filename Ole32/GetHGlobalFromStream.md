## GetHGlobalFromStream

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int GetHGlobalFromStream(
   IStream pstm,
   out IntPtr phglobal
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-gethglobalfromstream)
