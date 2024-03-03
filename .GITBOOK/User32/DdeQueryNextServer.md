## DdeQueryNextServer

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeQueryNextServer(
   IntPtr hConvList,
   IntPtr hConvPrev
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddequerynextserver)
