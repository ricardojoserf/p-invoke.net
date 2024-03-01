## NotifyServiceStatusChange

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool NotifyServiceStatusChange(
   IntPtr hService,
   uint dwNotifyMask,
   ref SERVICE_NOTIFY StatusInfo,
   IntPtr pfnNotifyCallback,
   IntPtr pContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-notifyservicestatuschangea)
