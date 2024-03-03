## CreateFileMoniker

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateFileMoniker(
   string lpszPathName,
   out IMoniker ppmk
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-createfilemoniker)
