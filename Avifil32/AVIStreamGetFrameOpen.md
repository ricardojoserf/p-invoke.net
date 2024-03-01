## AVIStreamGetFrameOpen

```
[DllImport("Avifil32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint AVIStreamGetFrameOpen(
   IntPtr pAVIStream,
   ref AVIGETFRAME arg
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/vfw/nf-vfw-avistreamgetframeopen)
