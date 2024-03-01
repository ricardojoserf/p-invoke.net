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

[Microsoft documentation](TODO)
