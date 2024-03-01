## LockServiceDatabase

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LockServiceDatabase(
   IntPtr hSCManager
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-lockservicedatabase)
