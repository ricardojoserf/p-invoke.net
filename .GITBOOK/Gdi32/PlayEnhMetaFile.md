## PlayEnhMetaFile

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PlayEnhMetaFile(
   IntPtr hdc,
   IntPtr hemf,
   in RECT lprect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-playenhmetafile)
