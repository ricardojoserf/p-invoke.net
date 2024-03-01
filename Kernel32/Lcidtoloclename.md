## Lcidtoloclename

```
[DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LCIDToLocaleName(
   uint Locale,
   StringBuilder lpName,
   int cchName,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-lcidtoloclename)
