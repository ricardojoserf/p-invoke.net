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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-wsaioclt)
