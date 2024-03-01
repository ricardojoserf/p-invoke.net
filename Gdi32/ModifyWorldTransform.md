## ModifyWorldTransform

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool ModifyWorldTransform(
   IntPtr hdc,
   ref XFORM lpXform,
   uint mode
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-modifyworldtransform)
