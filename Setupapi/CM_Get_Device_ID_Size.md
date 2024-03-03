## CM_Get_Device_ID_Size

```csharp
[DllImport("setupapi.dll", SetLastError = true)]
public static extern int CM_Get_Device_ID_Size(
   out int pulLen,
   uint dnDevInst,
   uint ulFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/cfgmgr32/nf-cfgmgr32-cm_get_device_id_size)
