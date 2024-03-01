## GetCharacterPlacement

```
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

[Microsoft documentation](TODO)
