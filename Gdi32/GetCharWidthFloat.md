## GetCharWidthFloat

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetCharWidthFloat(
   IntPtr hdc,
   uint iFirst,
   uint iLast,
   [Out] float[] lpBuffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharwidthfloata)
