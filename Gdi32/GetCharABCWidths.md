## GetCharABCWidths

```
[DllImport("gdi32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCharABCWidthsA(IntPtr hdc,
   uint iFirstChar,
   uint iLastChar,
   [Out] ABC[] lpabc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharabcwidthsa)
