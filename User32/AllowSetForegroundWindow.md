## AllowSetForegroundWindow

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AllowSetForegroundWindow(
   uint dwProcessId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-allowsetforegroundwindow)
