## ChangeWindowMessageFilter

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ChangeWindowMessageFilter(
   uint message,
   uint dwFlag
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-changewindowmessagefilter)
