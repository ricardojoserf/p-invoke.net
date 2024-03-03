## SetMiterLimit

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int SetMiterLimit(
   IntPtr hdc,
   float eNewLimit,
   float peOldLimit
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setmiterlimit)
