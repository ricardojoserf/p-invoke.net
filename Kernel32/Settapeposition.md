## Settapeposition

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetTapePosition(IntPtr hDevice,
   uint dwPositionMethod,
   IntPtr dwPartition,
   uint dwOffsetLow,
   uint dwOffsetHigh,
   [MarshalAs(UnmanagedType.Bool)] bool bImmediate
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-settapeposition)
