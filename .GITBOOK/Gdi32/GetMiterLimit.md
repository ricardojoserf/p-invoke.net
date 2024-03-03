## GetMiterLimit

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetMiterLimit(
   IntPtr hdc,
   out float peLimit
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getmiterlimit)
