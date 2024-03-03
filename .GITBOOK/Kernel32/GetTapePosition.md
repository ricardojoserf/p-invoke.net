## GetTapePosition

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetTapePosition(
   IntPtr hDevice,
   uint dwPositionType,
   out uint lpdwPartition,
   out uint lpdwOffsetLow,
   out uint lpdwOffsetHigh
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-gettapeposition)
