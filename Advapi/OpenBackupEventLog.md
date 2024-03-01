## OpenBackupEventLog

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysUInt)]
public static extern IntPtr OpenBackupEventLog(
   string lpUNCServerName,
   string lpFileName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-openbackupeventloga)
