## BackupEventLog

```csharp
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool BackupEventLog(
   IntPtr hEventLog,
   string lpBackupFileName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-backupeventloga)
