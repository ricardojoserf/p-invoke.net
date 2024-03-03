## CombineTransform

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool CombineTransform(
   out XFORM lpxformResult,
   [In] ref XFORM lpxform1,
   [In] ref XFORM lpxform2
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-combinetransform)
