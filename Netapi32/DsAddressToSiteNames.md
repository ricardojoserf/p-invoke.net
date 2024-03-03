## DsAddressToSiteNames

```csharp
[DllImport("netapi32.dll", SetLastError = true)]
public static extern uint DsAddressToSiteNames(
   string ComputerName,
   uint EntryCount,
   SOCKET_ADDRESS[] SocketAddresses,
   out IntPtr SiteNames
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dsgetdc/nf-dsgetdc-dsaddresstositenamesw)
