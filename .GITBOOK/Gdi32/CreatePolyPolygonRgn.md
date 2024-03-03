## CreatePolyPolygonRgn

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreatePolyPolygonRgn(
   [In] ref POINT apt,
   int[] asz,
   int cPoly,
   int fnPolyFillMode
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createpolypolygonrgn)
