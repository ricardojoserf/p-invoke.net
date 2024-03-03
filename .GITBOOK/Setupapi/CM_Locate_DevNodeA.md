## CM_Locate_DevNodeA

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern int CM_Locate_DevNodeA(
   out uint pdnDevInst,
   string pDeviceID,
   uint ulFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/cfgmgr32/nf-cfgmgr32-cm_locate_devnodea)
