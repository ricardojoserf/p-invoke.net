## PowerSettingAccessCheck

```csharp
[DllImport("powrprof.dll", SetLastError = true)]
public static extern uint PowerSettingAccessCheck(
   Guid PowerGuid
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-powersettingaccesscheck)
