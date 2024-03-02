## Setprocessworkingsetsize

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetProcessWorkingSetSize(IntPtr hProcess,
   IntPtr dwMinimumWorkingSetSize,
   IntPtr dwMaximumWorkingSetSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-setprocessworkingsetsize#:~:text=The%20minimum%20and%20maximum%20working%20set%20sizes%20affect%20the%20virtual,possible%20from%20the%20working%20set.)
