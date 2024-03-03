## GetPhysicallyInstalledSystemMemory

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetPhysicallyInstalledSystemMemory(
   out ulong TotalMemoryInKilobytes
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getphysicallyinstalledsystemmemory)
