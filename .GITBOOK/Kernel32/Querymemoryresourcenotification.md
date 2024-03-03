## Querymemoryresourcenotification

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool QueryMemoryResourceNotification(IntPtr ResourceNotificationHandle,
   out bool ResourceState
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-querymemoryresourcenotification)
