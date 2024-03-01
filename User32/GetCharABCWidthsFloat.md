## GetCharABCWidthsFloat

```
[DllImport("gdi32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCharABCWidthsFloatA(IntPtr hdc,
   uint iFirstChar,
   uint iLastChar,
   [Out] ABCFLOAT[] lpABCF
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharabcwidthsfloata)
