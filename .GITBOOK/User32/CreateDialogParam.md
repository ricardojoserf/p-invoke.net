## CreateDialogParam

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr CreateDialogParam(
   IntPtr hInstance,
   [In] IntPtr lpTemplateName,
   IntPtr hWndParent,
   [In] IntPtr lpDialogFunc,
   IntPtr dwInitParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createdialogparama)
