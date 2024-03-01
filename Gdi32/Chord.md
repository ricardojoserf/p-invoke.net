## Chord

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool Chord(
   IntPtr hdc,
   int xRadial1,
   int yRadial1,
   int xRadial2,
   int yRadial2,
   int xArc1,
   int yArc1,
   int xArc2,
   int yArc2
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-chord)
