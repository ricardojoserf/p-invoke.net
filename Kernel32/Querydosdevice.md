## Querydosdevice

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint QueryDosDevice(string lpDeviceName,
   StringBuilder lpTargetPath,
   uint ucchMax
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-querydosdevicew)
