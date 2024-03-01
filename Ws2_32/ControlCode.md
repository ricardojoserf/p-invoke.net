## ControlCode

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int ControlCode(
   uint dwIoControlCode,
   IntPtr lpInBuffer,
   uint nInBufferSize,
   IntPtr lpOutBuffer,
   uint nOutBufferSize,
   ref uint lpBytesReturned,
   IntPtr lpOverlapped,
   IntPtr lpCompletionRoutine
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/winsock/controlcode)
