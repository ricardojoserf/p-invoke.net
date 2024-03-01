## GetSystemMemoryDivision

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool GetSystemMemoryDivision(
   out uint lpdwStorePages,
   out uint lpdwRamPages,
   out uint lpdwPageSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getsystemmemorydivision)
