## GetStringTypeEx

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetStringTypeEx(
   uint Locale,
   uint dwInfoType,
   string lpSrcStr,
   int cchSrc,
   out ushort lpCharType
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getstringtypeexw)
