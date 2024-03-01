## GetMailslotInfo

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetMailslotInfo(
   SafeFileHandle hMailslot,
   IntPtr lpMaxMessageSize,
   out uint lpNextSize,
   out uint lpMessageCount,
   IntPtr lpReadTimeout
);
```

Microsoft documentation: (TODO)
