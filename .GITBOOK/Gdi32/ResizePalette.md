## ResizePalette

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint ResizePalette(
   IntPtr hpal,
   uint n
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-resizepalette)
