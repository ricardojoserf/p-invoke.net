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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/setjob)
