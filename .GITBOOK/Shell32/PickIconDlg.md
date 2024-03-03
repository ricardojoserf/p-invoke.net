## PickIconDlg

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int PickIconDlg(
   IntPtr hwndOwner,
   StringBuilder pszIconPath,
   uint cchIconPath,
   out int piIconIndex
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-pickicondlg)
