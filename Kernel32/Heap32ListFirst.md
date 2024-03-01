## Heap32ListFirst

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool Heap32ListFirst(
   IntPtr hSnapshot,
   ref HEAPLIST32 lphl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-heap32listfirst)
