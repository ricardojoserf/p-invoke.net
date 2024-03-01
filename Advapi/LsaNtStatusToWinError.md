## LsaNtStatusToWinError

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LsaNtStatusToWinError(
   uint Status
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ntstatus/nf-ntstatus-lsantstatustowinerror)
