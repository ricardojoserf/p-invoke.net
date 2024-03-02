## CoGetObject

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetObject(
   string pszName,
   BIND_OPTS pBindOptions,
   ref Guid riid,
   out IntPtr ppv
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-cogetobject)
