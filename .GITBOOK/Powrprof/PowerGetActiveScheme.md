## PowerGetActiveScheme

```csharp
[DllImport("powrprof.dll", SetLastError = true)]
public static extern uint PowerGetActiveScheme(
   IntPtr UserRootPowerKey,
   ref IntPtr ActivePolicyGuid
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/powersetting/nf-powersetting-powergetactivescheme)
