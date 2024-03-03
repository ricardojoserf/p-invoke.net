## AlignRects

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern void AlignRects(
   ref RECT prcPrimary,
   ref RECT prcSecondary,
   uint dwFlags
);
```

