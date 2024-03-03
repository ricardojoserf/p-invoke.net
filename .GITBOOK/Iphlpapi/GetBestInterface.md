## GetBestInterface

```csharp
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetBestInterface(
   uint DestAddr,
   out uint BestIfIndex
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getbestinterface)
