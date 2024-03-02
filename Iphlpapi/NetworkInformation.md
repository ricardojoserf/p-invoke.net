## NetworkInformation

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int NetworkInformation(
   ref IP_MIB_GET_ROW pInputData
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/dotnet/api/system.net.networkinformation?view=net-8.0)
