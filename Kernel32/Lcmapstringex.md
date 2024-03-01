## Lcmapstringex

```
[DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LCMapStringEx(string lpLocaleName,
   uint dwMapFlags,
   string lpSrcStr,
   int cchSrc,
   [Out] StringBuilder lpDestStr,
   int cchDest,
   IntPtr lpVersionInformation,
   IntPtr lpReserved,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-lcmapstringex)
