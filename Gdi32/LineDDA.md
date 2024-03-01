## LineDDA

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool LineDDA(
   int xStart,
   int yStart,
   int xEnd,
   int yEnd,
   [MarshalAs(UnmanagedType.FunctionPtr)] LINEDDAPROC lpProc,
   IntPtr lpData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-linedda)
