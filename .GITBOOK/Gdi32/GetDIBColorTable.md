## GetDIBColorTable

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetDIBColorTable(
   IntPtr hdc,
   uint iStart,
   uint cEntries,
   [Out] RGBQUAD[] pColors
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getdibcolortable)
