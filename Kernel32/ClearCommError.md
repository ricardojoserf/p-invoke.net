## ClearCommError

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ClearCommError(
   IntPtr hFile,
   out uint lpErrors,
   ref COMSTAT lpStat
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-clearcommerror)
