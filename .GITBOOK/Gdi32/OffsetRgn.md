## OffsetRgn

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int OffsetRgn(
   IntPtr hrgn,
   int nXOffset,
   int nYOffset
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-offsetrgn)
