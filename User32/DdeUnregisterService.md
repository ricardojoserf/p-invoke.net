## DdeUnregisterService

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeUnregisterService(
   IntPtr idInst,
   IntPtr hszService
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddeunregisterservice)
