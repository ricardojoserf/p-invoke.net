## ArcTo

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool ArcTo(
   IntPtr hdc,
   int nLeftRect,
   int nTopRect,
   int nRightRect,
   int nBottomRect,
   int nXRadial1,
   int nYRadial1,
   int nXRadial2,
   int nYRadial2
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-arcto)
