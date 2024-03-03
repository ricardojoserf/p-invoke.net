## FmtIdToPropStgName

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int FmtIdToPropStgName(
   ref Guid rfmtid,
   [MarshalAs(UnmanagedType.LPWStr)] out string oszName
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-fmtidtopropstgname)
