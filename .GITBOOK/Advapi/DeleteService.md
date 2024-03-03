## DeleteService

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DeleteService(
   IntPtr hService
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-deleteservice)
