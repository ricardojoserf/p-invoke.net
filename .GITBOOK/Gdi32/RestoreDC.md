## RestoreDC

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool RestoreDC(
   IntPtr hdc,
   int nSavedDC
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-restoredc)
