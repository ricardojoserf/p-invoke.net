## Virtualallocex

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.LPArray, SizeParamIndex = 1)]
public static extern IntPtr VirtualAllocEx(IntPtr hProcess,
   IntPtr lpAddress,
   UIntPtr dwSize,
   uint flAllocationType,
   uint flProtect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-virtualallocex)
