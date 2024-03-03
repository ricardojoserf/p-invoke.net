## NetUserModalsSet

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetUserModalsSet(
   string ServerName,
   uint Level,
   ref USER_MODALS_INFO_0 Buffer,
   out uint ParmError
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netusermodalsset)
