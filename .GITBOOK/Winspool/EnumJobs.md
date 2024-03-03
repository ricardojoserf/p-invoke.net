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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/enumjobs)
