## CoGetMalloc

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetMalloc(
   uint dwMemContext,
   out IMalloc ppMalloc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetmalloc)
