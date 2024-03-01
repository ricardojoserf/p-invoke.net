## CreateStreamOnHGlobal

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateStreamOnHGlobal(
   IntPtr hGlobal,
   bool fDeleteOnRelease,
   out IStream ppstm
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/objidl/nf-objidl-createstreamonhglobal)
