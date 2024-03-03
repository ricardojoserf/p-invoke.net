## CreateCursor

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr CreateCursor(
   IntPtr hInst,
   int xHotSpot,
   int yHotSpot,
   int nWidth,
   int nHeight,
   byte[] pvANDPlane,
   byte[] pvXORPlane
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createcursor)
