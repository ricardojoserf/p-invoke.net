## HeapAlloc

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr HeapAlloc(
   IntPtr hHeap,
   uint dwFlags,
   UIntPtr dwBytes
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapalloc)
