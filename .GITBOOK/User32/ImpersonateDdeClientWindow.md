## ImpersonateDdeClientWindow

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool ImpersonateDdeClientWindow(
   IntPtr hWndClient,
   IntPtr hWndServer,
   out uint pid
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dde/nf-dde-impersonateddeclientwindow)
