## NetShareSetInfo

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetShareSetInfo(
   string servername,
   string netname,
   uint level,
   ref SHARE_INFO_2 Buf,
   out uint parm_err
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmshare/nf-lmshare-netsharesetinfo)
