## RegCreateKeyEx

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RegCreateKeyEx(
   IntPtr hKey,
   string lpSubKey,
   int Reserved,
   string lpClass,
   int dwOptions,
   int samDesired,
   ref SECURITY_ATTRIBUTES lpSecurityAttributes,
   out IntPtr phkResult,
   out int lpdwDisposition
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcreatekeyexw)
