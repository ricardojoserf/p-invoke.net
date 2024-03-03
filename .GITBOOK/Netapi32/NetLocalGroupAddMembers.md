## NetLocalGroupAddMembers

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetLocalGroupAddMembers(
   string ServerName,
   string GroupName,
   uint Level,
   ref LOCALGROUP_MEMBERS_INFO_0 Buf,
   uint totalentries
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netlocalgroupaddmembers)
