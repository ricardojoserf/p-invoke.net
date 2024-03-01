## MWT_

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint SetWorldTransform(
   IntPtr hdc,
   ref XFORM lpXform
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setworldtransform)
