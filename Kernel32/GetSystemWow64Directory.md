## GetSystemWow64Directory

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetSystemWow64Directory(
   StringBuilder lpBuffer,
   uint uSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wow64apiset/nf-wow64apiset-getsystemwow64directorya)
