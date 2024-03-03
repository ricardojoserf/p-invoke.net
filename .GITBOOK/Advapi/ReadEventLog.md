## ReadEventLog

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReadEventLog(
   IntPtr hEventLog,
   uint dwReadFlags,
   uint dwRecordOffset,
   [Out] byte[] lpBuffer,
   uint nNumberOfBytesToRead,
   out uint pnBytesRead,
   out uint pnMinNumberOfBytesNeeded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-readeventloga)
