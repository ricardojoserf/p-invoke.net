## NtOpenDirectoryObject

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtOpenDirectoryObject(
   out IntPtr DirectoryHandle,
   uint DesiredAccess,
   IntPtr ObjectAttributes
);
```

Microsoft documentation: (TODO)
