## CM_Get_Device_ID

```csharp
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int CM_Get_Device_ID(
   uint dnDevInst,
   StringBuilder Buffer,
   int BufferLen,
   uint ulFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/cfgmgr32/nf-cfgmgr32-cm_get_device_idw)
