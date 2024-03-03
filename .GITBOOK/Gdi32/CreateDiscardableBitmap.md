## CreateDiscardableBitmap

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreateDiscardableBitmap(
   IntPtr hdc,
   int nWidth,
   int nHeight
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-creatediscardablebitmap)
