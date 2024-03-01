## SHChangeNotify

```
[DllImport("shell32.dll")]
public static extern void SHChangeNotify(
   uint wEventId,
   uint uFlags,
   IntPtr dwItem1,
   IntPtr dwItem2
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shchangenotify)
