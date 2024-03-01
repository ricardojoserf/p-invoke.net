## WriteStringStream

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int WriteStringStream(
   IStream pStm,
   [MarshalAs(
   UnmanagedType.LPWStr)] string psz
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-writestringstream)
