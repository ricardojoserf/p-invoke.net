## Mapuserphysicalpages

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool MapUserPhysicalPages(IntPtr VirtualAddresses,
   uint NumberOfPages,
   IntPtr PageArray
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-mapuserphysicalpages)
