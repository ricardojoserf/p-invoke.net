## GetRegisteredRawInputDevices

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern uint GetRegisteredRawInputDevices(
   IntPtr pRawInputDevices,
   ref uint puiNumDevices,
   uint cbSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getregisteredrawinputdevices)
