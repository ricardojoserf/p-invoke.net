## ACLineStatus

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool GetSystemPowerStatus(out ACLineStatus acLineStatus,
   out BatteryFlag batteryFlag
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getsystempowerstatus)
