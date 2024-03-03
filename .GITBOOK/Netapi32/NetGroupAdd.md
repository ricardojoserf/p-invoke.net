## NetGroupAdd

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetGroupAdd(
   string ServerName,
   uint Level,
   ref GROUP_INFO_0 Buf,
   out uint ParmError
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netgroupadd)
