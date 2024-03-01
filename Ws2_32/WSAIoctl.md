## WSAIoctl

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSAIoctl(
   IntPtr s,
   uint dwIoControlCode,
   IntPtr lpvInBuffer,
   uint cbInBuffer,
   IntPtr lpvOutBuffer,
   uint cbOutBuffer,
   ref uint lpcbBytesReturned,
   IntPtr lpOverlapped,
   IntPtr lpCompletionRoutine
);
```

Microsoft documentation: (TODO)
