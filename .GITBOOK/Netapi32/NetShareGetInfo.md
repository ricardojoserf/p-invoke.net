## NetShareGetInfo

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetShareGetInfo(
   string servername,
   string netname,
   uint level,
   out IntPtr Buffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmshare/nf-lmshare-netsharegetinfo)
