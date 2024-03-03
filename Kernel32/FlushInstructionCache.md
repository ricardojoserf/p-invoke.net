## FlushInstructionCache

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FlushInstructionCache(
   IntPtr hProcess,
   IntPtr lpBaseAddress,
   uint dwSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-flushinstructioncache)
