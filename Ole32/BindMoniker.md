## BindMoniker

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int BindMoniker(
   IMoniker pmk,
   uint grfOpt,
   ref Guid iidResult,
   out object ppvResult
);
```

Microsoft documentation: (TODO)
