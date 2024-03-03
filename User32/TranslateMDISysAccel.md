## TranslateMDISysAccel

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool TranslateMDISysAccel(
   IntPtr hWndClient,
   ref MSG lpMsg
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-translatemdisysaccel)
