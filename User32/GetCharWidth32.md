## GetCharWidth32

```
[DllImport("gdi32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCharWidth32A(IntPtr hdc,
   uint iFirstChar,
   uint iLastChar,
   [Out] float[] lpBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharwidth32a)
