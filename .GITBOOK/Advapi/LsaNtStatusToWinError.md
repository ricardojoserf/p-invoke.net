## LsaNtStatusToWinError

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LsaNtStatusToWinError(
   uint Status
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsantstatustowinerror)
