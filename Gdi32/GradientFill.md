## GradientFill

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GradientFill(
   IntPtr hdc,
   TRIVERTEX[] pVertex,
   uint dwNumVertex,
   IntPtr pMesh,
   uint dwNumMesh,
   uint dwMode
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gradientfill)
