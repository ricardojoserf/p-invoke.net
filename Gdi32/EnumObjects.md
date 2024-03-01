## EnumObjects

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int EnumObjects(
   IntPtr hdc,
   int nObjectType,
   GOBJENUMPROC lpObjectFunc,
   IntPtr lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-enumobjects)
