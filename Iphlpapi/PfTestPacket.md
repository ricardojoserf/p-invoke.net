## PfTestPacket

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int PfTestPacket(
   ref IP_ADAPTER_BINDING_INFO AdapterInfo,
   IntPtr IoPacket,
   ref PFTEST_PACKET_PARAMETERS PacketParameters
);
```

[Microsoft documentation](TODO)
