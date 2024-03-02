## SHInvokePrinterCommand

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern bool SHInvokePrinterCommand(
   IntPtr hwnd,
   uint uAction,
   string lpBuf1,
   string lpBuf2,
   bool fModal
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shinvokeprintercommanda)
