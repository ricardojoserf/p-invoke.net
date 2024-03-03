## GetMailslotInfo

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetMailslotInfo(
   SafeFileHandle hMailslot,
   IntPtr lpMaxMessageSize,
   out uint lpNextSize,
   out uint lpMessageCount,
   IntPtr lpReadTimeout
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getmailslotinfo)
