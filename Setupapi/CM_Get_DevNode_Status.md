## CM_Get_DevNode_Status

```
[DllImport("setupapi.dll", SetLastError = true)]
public static extern int CM_Get_DevNode_Status(
   out int pulStatus,
   out int pulProblemNumber,
   uint dnDevInst,
   uint ulFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/cfgmgr32/nf-cfgmgr32-cm_get_devnode_status)
