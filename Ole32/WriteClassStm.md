## WriteClassStm

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int WriteClassStm(
   IStream pStm,
   ref Guid rclsid
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-writeclassstm)
