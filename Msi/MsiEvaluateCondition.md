## MsiEvaluateCondition

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiEvaluateCondition(
   IntPtr hInstall,
   [MarshalAs(UnmanagedType.LPTStr)] string szCondition
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msievaluateconditionw)
