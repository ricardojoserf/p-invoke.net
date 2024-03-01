## CreateDialogIndirectParam

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr CreateDialogIndirectParam(
   IntPtr hInstance,
   [In] IntPtr lpTemplate,
   IntPtr hWndParent,
   [In] IntPtr lpDialogFunc,
   IntPtr dwInitParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createdialogindirectparama)
