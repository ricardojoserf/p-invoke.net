## GetAdaptersAddresses

```csharp
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetAdaptersAddresses(
   uint Family,
   uint Flags,
   IntPtr Reserved,
   IntPtr AdapterAddresses,
   ref uint SizePointer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getadaptersaddresses)
