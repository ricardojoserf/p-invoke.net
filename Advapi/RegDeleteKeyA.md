## RegDeleteKeyA

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegDeleteKeyA(
   IntPtr hKey,
   string lpSubKey
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeya)
