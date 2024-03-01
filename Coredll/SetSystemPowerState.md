## SetSystemPowerState

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetSystemPowerState(
   string psState,
   int StateFlags,
   int Options
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/nspapi/nf-nspapi-setsystempowerstate)
