## ClearEventLog

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ClearEventLog(
   IntPtr hEventLog,
   string lpBackupFileName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-cleareventloga)
