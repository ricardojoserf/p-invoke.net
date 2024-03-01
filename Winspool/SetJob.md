## SetJob

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool SetJob(
   IntPtr hPrinter,
   uint JobId,
   uint Level,
   IntPtr pJob,
   uint Command
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-setjoba)
