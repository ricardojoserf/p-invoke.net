## SetSystemPowerState

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetSystemPowerState(
   string psState,
   int StateFlags,
   int Options
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setsystempowerstate)
