## DeviceIOControl

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern int DeviceIOControl(
   IntPtr hDevice,
   uint dwIoControlCode,
   IntPtr lpInBuffer,
   uint nInBufferSize,
   IntPtr lpOutBuffer,
   uint nOutBufferSize,
   ref uint lpBytesReturned,
   IntPtr lpOverlapped
);
```

Microsoft documentation: (TODO)
