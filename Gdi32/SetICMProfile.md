## SetICMProfile

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetICMProfile(
   IntPtr hdc,
   string lpFileName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-seticmprofilea)
