## CM_Get_DevNode_Registry_Property

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int CM_Get_DevNode_Registry_Property(
   uint dnDevInst,
   int ulProperty,
   out int pulRegDataType,
   IntPtr pBuffer,
   ref int pulLength,
   int ulFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/cfgmgr32/nf-cfgmgr32-cm_get_devnode_registry_propertyw)
