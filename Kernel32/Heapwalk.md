## Heapwalk

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool HeapWalk(
   IntPtr hHeap,
   ref PROCESS_HEAP_ENTRY lpEntry
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapwalk)
