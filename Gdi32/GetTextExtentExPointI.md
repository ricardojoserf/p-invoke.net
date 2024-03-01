## GetTextExtentExPointI

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetTextExtentExPointI(
   IntPtr hdc,
   [In] ushort[] lpwszString,
   int cchString,
   int nMaxExtent,
   [Out] int[] lpnFit,
   [Out] int[] alpDx,
   ref SIZE lpSize
);
```

Microsoft documentation: (TODO)
