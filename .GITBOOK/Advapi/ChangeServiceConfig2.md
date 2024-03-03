## ChangeServiceConfig2

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ChangeServiceConfig2(
   IntPtr hService,
   uint dwInfoLevel,
   IntPtr lpInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-changeserviceconfig2a)
