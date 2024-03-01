## EnumJobs

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool EnumJobs(
   IntPtr hPrinter,
   uint FirstJob,
   uint NoJobs,
   uint Level,
   IntPtr pJob,
   uint cbBuf,
   out uint pcbNeeded,
   out uint pcReturned
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-enumjobsa)
