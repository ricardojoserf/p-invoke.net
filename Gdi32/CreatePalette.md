## CreatePalette

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreatePalette(
   [In] ref LOGPALETTE lplgpl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createpalette)
