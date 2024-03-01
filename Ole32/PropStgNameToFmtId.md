## PropStgNameToFmtId

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int PropStgNameToFmtId(
   [MarshalAs(UnmanagedType.LPWStr)] string oszName,
   out Guid pfmtid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/propidlbase/nf-propidlbase-propstgnametofmtid)
