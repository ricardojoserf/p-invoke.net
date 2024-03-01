## CoGetCancelObject

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetCancelObject(
   uint dwThreadId,
   ref Guid iid,
   out object ppv
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetcancelobject)
