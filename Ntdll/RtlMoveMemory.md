## RtlMoveMemory

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern void RtlMoveMemory(
   IntPtr Destination,
   IntPtr Source,
   uint Length
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-rtlmovememory)
