## WSAEnumNameSpaceProviders

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSAEnumNameSpaceProviders(
   ref uint lpdwBufferLength,
   IntPtr lpnspBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-wsaenumnamespaceprovidersa)
