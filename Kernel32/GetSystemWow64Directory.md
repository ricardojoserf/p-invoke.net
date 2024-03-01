## GetSystemWow64Directory

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetSystemWow64Directory(
   StringBuilder lpBuffer,
   uint uSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemwow64directoryw)
