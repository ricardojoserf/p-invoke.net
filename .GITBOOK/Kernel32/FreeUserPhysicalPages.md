## FreeUserPhysicalPages

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FreeUserPhysicalPages(
   IntPtr hProcess,
   ref ulong lpNumberOfPages,
   ulong[] userPfnArray
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-freeuserphysicalpages)
