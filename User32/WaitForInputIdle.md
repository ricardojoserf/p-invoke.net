## WaitForInputIdle

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern uint WaitForInputIdle(
   IntPtr hProcess,
   uint dwMilliseconds
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-waitforinputidle)
