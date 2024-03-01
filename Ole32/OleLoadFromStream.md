## OleLoadFromStream

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleLoadFromStream(
   IStream pStm,
   ref Guid riid,
   out object ppvObj
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-oleloadfromstream)
