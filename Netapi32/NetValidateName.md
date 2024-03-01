## NetValidateName

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetValidateName(
   string ServerName,
   string Name,
   string Account,
   string Password,
   NETSETUP_NAME_TYPE NameType
);
```

Microsoft documentation: (TODO)
