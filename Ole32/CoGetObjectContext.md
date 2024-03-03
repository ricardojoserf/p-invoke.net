## CoGetObjectContext

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetObjectContext(
   ref Guid riid,
   out object ppv
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetobjectcontext)
