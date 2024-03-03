## CreateFontIndirectEx

```csharp
[DllImport("gdi32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern IntPtr CreateFontIndirectEx(
   [In] ref ENUMLOGFONTEXDV lplf
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createfontindirectexa)
