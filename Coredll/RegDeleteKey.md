## RegDeleteKey

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RegDeleteKey(
   IntPtr hKey,
   string lpSubKey
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeyw)
