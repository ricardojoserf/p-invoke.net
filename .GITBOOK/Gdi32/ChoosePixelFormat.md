## ChoosePixelFormat

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int ChoosePixelFormat(
   IntPtr hdc,
   [In] ref PIXELFORMATDESCRIPTOR ppfd
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-choosepixelformat)
