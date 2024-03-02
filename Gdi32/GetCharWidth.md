## GetCharWidth

```
[DllImport("gdi32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCharWidthA(IntPtr hdc,
   uint iFirstChar,
   uint iLastChar,
   [Out] int[] lpBuffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharwidtha)
