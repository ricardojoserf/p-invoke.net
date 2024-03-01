## GenerateConsoleCtrlEvent

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GenerateConsoleCtrlEvent(
   uint dwCtrlEvent,
   uint dwProcessGroupId
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-generateconsolectrlevent)
