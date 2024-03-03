## CM_Get_Device_IDA

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern int CM_Get_Device_IDA(
   uint dnDevInst,
   StringBuilder Buffer,
   int BufferLen,
   uint ulFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/cfgmgr32/nf-cfgmgr32-cm_get_device_ida)
