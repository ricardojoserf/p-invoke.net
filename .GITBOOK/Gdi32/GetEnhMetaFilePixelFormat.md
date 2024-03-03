## GetEnhMetaFilePixelFormat

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetEnhMetaFilePixelFormat(
   IntPtr hemf,
   uint cbBuffer,
   ref PIXELFORMATDESCRIPTOR ppfd
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getenhmetafilepixelformat)
