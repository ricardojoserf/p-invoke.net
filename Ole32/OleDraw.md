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

[Microsoft documentation](TODO)
