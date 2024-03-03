## GetWriteWatch

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetWriteWatch(
   uint dwFlags,
   IntPtr lpBaseAddress,
   uint dwRegionSize,
   [Out] IntPtr lpAddresses,
   out uint lpdwCount,
   out uint lpdwGranularity
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-getwritewatch)
