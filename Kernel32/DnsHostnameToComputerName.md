## DnsHostnameToComputerName

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DnsHostnameToComputerName(
   string Hostname,
   StringBuilder ComputerName,
   ref uint nSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-dnshostnametocomputernamea)
