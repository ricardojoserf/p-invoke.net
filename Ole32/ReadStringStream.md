## ReadStringStream

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int ReadStringStream(
   IStream pStm,
   [MarshalAs(UnmanagedType.LPWStr)] out string ppsz
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-readstringstream)
