## CreateGenericComposite

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateGenericComposite(
   ref IMoniker pmkFirst,
   ref IMoniker pmkRest,
   out IMoniker ppmkComposite
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/objidl/nf-objidl-creategenericcomposite)
