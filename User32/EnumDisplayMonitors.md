## EnumDisplayMonitors

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumDisplayMonitors(
   IntPtr hdc,
   IntPtr lprcClip,
   EnumMonitorsProc lpfnEnum,
   IntPtr dwData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enumdisplaymonitors)
