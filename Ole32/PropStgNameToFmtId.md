## PropStgNameToFmtId

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int PropStgNameToFmtId(
   [MarshalAs(UnmanagedType.LPWStr)] string oszName,
   out Guid pfmtid
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-propstgnametofmtid)
