## CreateBindCtx

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateBindCtx(
   uint reserved,
   out IBindCtx ppbc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-createbindctx)
