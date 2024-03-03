## GetInterfaceInfo

```csharp
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetInterfaceInfo(
   IntPtr pIfTable,
   ref uint dwOutBufLen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getinterfaceinfo)
