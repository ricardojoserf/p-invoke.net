## CoGetCallContext

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetCallContext(
   ref Guid riid,
   out object ppv
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetcallcontext)
