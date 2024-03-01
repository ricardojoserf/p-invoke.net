## CM_Request_Device_Eject

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int CM_Request_Device_Eject(
   uint dnDevInst,
   out int pVetoType,
   StringBuilder pszVetoName,
   int ulNameLength,
   uint ulFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/cfgmgr32/nf-cfgmgr32-cm_request_device_eject)
