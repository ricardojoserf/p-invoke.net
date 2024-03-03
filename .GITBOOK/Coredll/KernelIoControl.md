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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/ms957125(v=msdn.10))
