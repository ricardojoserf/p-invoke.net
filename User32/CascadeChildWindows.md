## CascadeChildWindows

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern uint CascadeChildWindows(
   IntPtr hWndParent,
   uint wHow
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-cascadewindows)
