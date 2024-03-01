## GetStringType

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetStringType(
   uint Locale,
   uint dwInfoType,
   string lpSrcStr,
   int cchSrc,
   out ushort lpCharType
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getstringtypew)
