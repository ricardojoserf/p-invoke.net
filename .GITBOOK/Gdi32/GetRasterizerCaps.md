## GetRasterizerCaps

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetRasterizerCaps(
   ref RASTERIZER_STATUS lprs,
   uint cb
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getrasterizercaps)
