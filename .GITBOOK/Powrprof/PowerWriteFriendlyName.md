## PowerWriteFriendlyName

```csharp
[DllImport("powrprof.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern uint PowerWriteFriendlyName(
   IntPtr RootPowerKey,
   ref Guid SchemeGuid,
   ref Guid SubGroupOfPowerSetting,
   ref Guid PowerSetting,
   string Buffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-powerwritefriendlyname)
