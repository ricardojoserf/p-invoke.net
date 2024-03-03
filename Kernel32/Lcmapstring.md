## Lcmapstring

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LCMapString(uint Locale,
   uint dwMapFlags,
   string lpSrcStr,
   int cchSrc,
   [Out] StringBuilder lpDestStr,
   int cchDest
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-lcmapstringw)
