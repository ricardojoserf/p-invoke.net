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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/ms960831(v%3Dmsdn.10))
