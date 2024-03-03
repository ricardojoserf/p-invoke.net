## CreatePen

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreatePen(
   uint fnPenStyle,
   int nWidth,
   uint crColor
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createpen)
