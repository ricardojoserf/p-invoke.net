## DialogBoxIndirectParam

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DialogBoxIndirectParam(
   IntPtr hInstance,
   [In] IntPtr hDialogTemplate,
   IntPtr hWndParent,
   [In] IntPtr lpDialogFunc,
   IntPtr dwInitParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-dialogboxindirectparama)
