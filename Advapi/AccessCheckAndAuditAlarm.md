## AccessCheckAndAuditAlarm

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AccessCheckAndAuditAlarm(
   string SubsystemName,
   IntPtr hObject,
   IntPtr pObjectName,
   IntPtr pSecurityDescriptor,
   uint DesiredAccess,
   [In] ref GENERIC_MAPPING GenericMapping,
   [MarshalAs(UnmanagedType.Bool)] bool ObjectCreation,
   out uint GrantedAccess,
   [MarshalAs(UnmanagedType.Bool)] out bool AccessStatus,
   out bool pfGenerateOnClose
);
```

[Microsoft documentation](TODO)
