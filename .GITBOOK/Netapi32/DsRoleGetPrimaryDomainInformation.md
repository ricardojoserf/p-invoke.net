## DsRoleGetPrimaryDomainInformation

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint DsRoleGetPrimaryDomainInformation(
   string ServerName,
   DSROLE_MACHINE_ROLE Role,
   out IntPtr Buffer
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dsrole/nf-dsrole-dsrolegetprimarydomaininformation)
