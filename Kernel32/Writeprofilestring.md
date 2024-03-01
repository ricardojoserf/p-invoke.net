## Writeprofilestring

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteProfileString(string lpAppName,
   string lpKeyName,
   string lpString
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-writeprofilestringw)
