## CreateIcon

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr CreateIcon(
   IntPtr hInstance,
   int nWidth,
   int nHeight,
   byte cPlanes,
   byte cBitsPixel,
   byte[] lpbANDbits,
   byte[] lpbXORbits
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createicon)
