## Registerserviceprocess

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool RegisterServiceProcess(
   uint dwProcessId,
   uint dwServiceType
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-registerserviceprocess)
