## Arc

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool Arc(
   IntPtr hdc,
   int nLeftRect,
   int nTopRect,
   int nRightRect,
   int nBottomRect,
   int nXStartArc,
   int nYStartArc,
   int nXEndArc,
   int nYEndArc
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-arc)
