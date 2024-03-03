## BindMoniker

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int BindMoniker(
   IMoniker pmk,
   uint grfOpt,
   ref Guid iidResult,
   out object ppvResult
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-bindmoniker)
