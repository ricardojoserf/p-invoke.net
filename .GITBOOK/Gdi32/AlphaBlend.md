## AlphaBlend

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool AlphaBlend(
   IntPtr hdcDest,
   int xoriginDest,
   int yoriginDest,
   int wDest,
   int hDest,
   IntPtr hdcSrc,
   int xoriginSrc,
   int yoriginSrc,
   int wSrc,
   int hSrc,
   BLENDFUNCTION ftn
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-alphablend)
