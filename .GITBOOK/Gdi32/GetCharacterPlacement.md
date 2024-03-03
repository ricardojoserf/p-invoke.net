## GetCharacterPlacement

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetCharacterPlacement(
   IntPtr hdc,
   string lpString,
   int nCount,
   int nMaxExtent,
   [Out] GCP_RESULTS lpResults,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharacterplacementa)
