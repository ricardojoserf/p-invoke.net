## ActivateKeyboardLayout

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr ActivateKeyboardLayout(
   IntPtr hkl,
   uint Flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-activatekeyboardlayout)
