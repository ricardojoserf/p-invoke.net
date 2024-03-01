## GetObject

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int GetObject(
   IntPtr hgdiobj,
   int cbBuffer,
   ref BITMAP lpvObject
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getobjecta)
