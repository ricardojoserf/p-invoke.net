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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-kerneliocontrol)
