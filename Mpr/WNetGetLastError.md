## WNetGetLastError

```
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetGetLastError(
   out uint lpError,
   StringBuilder lpErrorBuf,
   uint nErrorBufSize,
   StringBuilder lpNameBuf,
   uint nNameBufSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetgetlasterrora)
