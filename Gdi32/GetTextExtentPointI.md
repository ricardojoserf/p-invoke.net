## GetTextExtentPointI

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetTextExtentPointI(
   IntPtr hdc,
   [In] ushort[] pgiIn,
   int cgi,
   ref SIZE psize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gettextextentpointi)
