## DdeUnregister

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeUnregister(
   IntPtr idInst,
   IntPtr hsz,
   IntPtr hConv
);
```

