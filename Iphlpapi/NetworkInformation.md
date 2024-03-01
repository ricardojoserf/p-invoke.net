## NetworkInformation

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int NetworkInformation(
   ref IP_MIB_GET_ROW pInputData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-networkinformation)
