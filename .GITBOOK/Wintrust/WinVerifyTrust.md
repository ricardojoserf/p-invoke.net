## WinVerifyTrust

```
[DllImport("wintrust.dll", SetLastError = true)]
public static extern uint WinVerifyTrust(
   IntPtr hWnd,
   IntPtr pgActionID,
   IntPtr pWinTrustData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wintrust/nf-wintrust-winverifytrust)
