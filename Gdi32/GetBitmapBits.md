## GetBitmapBits

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int GetBitmapBits(
   IntPtr hbit,
   int cb,
   [Out] byte[] lpbits
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getbitmapbits)
