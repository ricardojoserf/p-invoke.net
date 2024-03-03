## GetAncestor

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr GetAncestor(
   IntPtr hwnd,
   uint gaFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getancestor)
