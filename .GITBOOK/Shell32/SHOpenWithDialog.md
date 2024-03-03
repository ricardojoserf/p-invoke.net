## SHOpenWithDialog

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHOpenWithDialog(
   IntPtr hwnd,
   ref OPENASINFO pOAI
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shopenwithdialog)
