## AVIStreamRead

```
[DllImport("Avifil32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint AVIStreamRead(
   IntPtr pAVIStream,
   int lStart,
   int lSamples,
   IntPtr lpBuffer,
   int cbBuffer,
   IntPtr plBytes,
   IntPtr plSamples
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/vfw/nf-vfw-avistreamread)
