## HeapFree

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool HeapFree(
   IntPtr hHeap,
   uint dwFlags,
   IntPtr lpMem
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapfree)
