## SendARP

```csharp
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint SendARP(
   uint DestIP,
   uint SrcIP,
   byte[] pMacAddr,
   ref uint PhyAddrLen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-sendarp)
