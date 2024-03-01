## MsiEnableLog

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiEnableLog(
   uint dwLogMode,
   [MarshalAs(
   UnmanagedType.LPTStr)] string szLogFile,
   uint dwLogAttributes
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msienablelogw)
