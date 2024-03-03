## GetDevicePowerState

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetDevicePowerState(
   IntPtr hDevice,
   [MarshalAs(UnmanagedType.Bool)] out bool pfOn
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getdevicepowerstate)
