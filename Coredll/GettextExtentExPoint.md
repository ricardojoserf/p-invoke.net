## GettextExtentExPoint

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool GettextExtentExPoint(
   IntPtr hdc,
   string lpszString,
   int cchString,
   int nMaxExtent,
   out int lpnFit,
   out int[] alpDx,
   out SIZE lpSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gettextextentexpointw)
