## BackupEventLog

```
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool BackupEventLog(
   IntPtr hEventLog,
   string lpBackupFileName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-backupeventloga)
