## DsGetDcNext

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint DsGetDcNext(
   IntPtr GetDcContextHandle,
   ref uint SockAddressCount,
   out SOCKET_ADDRESS[] SocketAddresses,
   out IntPtr SiteNames
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dsgetdc/nf-dsgetdc-dsgetdcnextw)
