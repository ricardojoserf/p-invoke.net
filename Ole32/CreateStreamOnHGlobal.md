## CreateStreamOnHGlobal

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateStreamOnHGlobal(
   IntPtr hGlobal,
   bool fDeleteOnRelease,
   out IStream ppstm
);
```

Microsoft documentation: (TODO)
