## GetComboBoxInfo

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetComboBoxInfo(
   IntPtr hwndCombo,
   ref COMBOBOXINFO pcbi
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getcomboboxinfo)
