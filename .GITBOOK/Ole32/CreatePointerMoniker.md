## CreatePointerMoniker

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreatePointerMoniker(
   IUnknown punk,
   out IMoniker ppmk
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-createpointermoniker)
