## CascadeWindows

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern uint CascadeWindows(
   IntPtr hwndParent,
   uint wHow,
   [In] ref RECT lpRect,
   uint cKids,
   [In] IntPtr lpKids
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-cascadewindows)
