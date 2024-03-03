## UnregisterHotKey

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool UnregisterHotKey(
   IntPtr hWnd,
   int id
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-unregisterhotkey)
