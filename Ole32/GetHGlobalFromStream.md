## GetHGlobalFromStream

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int GetHGlobalFromStream(
   IStream pstm,
   out IntPtr phglobal
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-gethglobalfromstream)
