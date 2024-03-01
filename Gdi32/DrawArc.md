## DrawArc

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool DrawArc(
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

Microsoft documentation: (TODO)
