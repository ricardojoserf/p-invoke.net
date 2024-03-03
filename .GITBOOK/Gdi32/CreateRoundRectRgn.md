## CreateRoundRectRgn

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreateRoundRectRgn(
   int nLeftRect,
   int nTopRect,
   int nRightRect,
   int nBottomRect,
   int nWidthEllipse,
   int nHeightEllipse
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createroundrectrgn)
