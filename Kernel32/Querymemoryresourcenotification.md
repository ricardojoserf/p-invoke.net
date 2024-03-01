## Querymemoryresourcenotification

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool QueryMemoryResourceNotification(
   IntPtr ResourceNotificationHandle,
   out bool ResourceState
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-querymemoryresourcenotification)
