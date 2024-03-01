## DnsHostnameToComputerName

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DnsHostnameToComputerName(
   string Hostname,
   StringBuilder ComputerName,
   ref uint nSize
);
```

Microsoft documentation: (TODO)
