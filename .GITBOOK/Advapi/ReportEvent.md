## ReportEvent

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReportEvent(
   IntPtr hEventLog,
   uint wType,
   ushort wCategory,
   uint dwEventID,
   IntPtr lpUserSid,
   ushort wNumStrings,
   uint dwDataSize,
   string[] lpStrings,
   IntPtr lpRawData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-reporteventa)
