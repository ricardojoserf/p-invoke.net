## SetSysColors

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetSysColors(
   int cElements,
   [In] int[] lpaElements,
   [In] COLORREF[] lpaRgbValues
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setsyscolors)
