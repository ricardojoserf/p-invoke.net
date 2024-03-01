## ZeroMemory

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern void ZeroMemory(
   IntPtr dest,
   uint size
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-zeromemory)
