## SetBitmapBits

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int SetBitmapBits(
   IntPtr hbmp,
   uint cb,
   byte[] lpBits
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setbitmapbits)
