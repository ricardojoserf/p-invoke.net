## GetSystemPowerStatus

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetSystemPowerStatus(
   out SYSTEM_POWER_STATUS lpSystemPowerStatus
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getsystempowerstatus)
