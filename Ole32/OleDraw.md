## OleDraw

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleDraw(
   [MarshalAs(UnmanagedType.Interface)] object pUnknown,
   uint dwAspect,
   IntPtr hdcDraw,
   ref RECT lprcBounds
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/oleidl/nf-oleidl-oledraw)
