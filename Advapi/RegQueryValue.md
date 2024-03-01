## RegQueryValue

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegQueryValue(
   IntPtr hKey,
   string lpSubKey,
   StringBuilder lpData,
   ref uint lpcbData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryvaluea)
