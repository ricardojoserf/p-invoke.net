## RegisterRawInputDevices

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool RegisterRawInputDevices(
   RAWINPUTDEVICE[] pRawInputDevices,
   uint uiNumDevices,
   uint cbSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-registerrawinputdevices)
