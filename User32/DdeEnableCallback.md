## DdeEnableCallback

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeEnableCallback(
   IntPtr idInst,
   IntPtr hConv,
   uint wCmd
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddeenablecallback)
