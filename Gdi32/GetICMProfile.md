## GetICMProfile

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetICMProfile(
   IntPtr hdc,
   ref uint pBufSize,
   StringBuilder pszFilename
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-geticmprofilea)
