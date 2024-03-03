## ExcludeClipRect

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int ExcludeClipRect(
   IntPtr hdc,
   int nLeftRect,
   int nTopRect,
   int nRightRect,
   int nBottomRect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-excludecliprect)
