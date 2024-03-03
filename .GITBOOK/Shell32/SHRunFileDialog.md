## SHRunFileDialog

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHRunFileDialog(
   IntPtr hwnd,
   ref IShellItem psi,
   IntPtr pszTitle,
   IntPtr pszOk,
   IntPtr pszCancel,
   uint dwFlags
);
```

