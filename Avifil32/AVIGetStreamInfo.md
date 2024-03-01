## AVIGetStreamInfo

```
[DllImport("Avifil32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint AVIGetStreamInfo(
   IntPtr pAVIStream,
   ref AVISTREAMINFO psi,
   int lSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/vfw/nf-vfw-avigetstreaminfoa)
