## WNetGetUniversalName

```
[DllImport("Mpr.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint WNetGetUniversalName(
   string lpLocalPath,
   uint dwInfoLevel,
   IntPtr lpBuffer,
   ref uint lpBufferSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetgetuniversalnamea)
