## NetApiBufferAllocate

```
[DllImport("netapi32.dll", SetLastError = true)]
public static extern uint NetApiBufferAllocate(
   uint ByteSize,
   out IntPtr Buffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmapibuf/nf-lmapibuf-netapibufferallocate)
