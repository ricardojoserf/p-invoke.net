## CreateToolhelp32Snapshot

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeSnapshotHandle CreateToolhelp32Snapshot(
   SnapshotFlags dwFlags,
   uint th32ProcessID
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-createtoolhelp32snapshot)
