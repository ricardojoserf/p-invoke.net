## FmtIdToPropStgName

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int FmtIdToPropStgName(
   ref Guid rfmtid,
   [MarshalAs(UnmanagedType.LPWStr)] out string oszName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/propidlbase/nf-propidlbase-fmtidtopropstgname)
