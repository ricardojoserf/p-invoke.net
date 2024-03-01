## KernelIoControl

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern int KernelIoControl(
   int dwIoControlCode,
   IntPtr lpInBuf,
   int nInBufSize,
   IntPtr lpOutBuf,
   int nOutBufSize,
   out int lpBytesReturned
);
```

Microsoft documentation: (TODO)
