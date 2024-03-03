## ioctlsocket

```csharp
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int ioctlsocket(
   IntPtr s,
   long cmd,
   ref uint argp
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-ioctlsocket)
