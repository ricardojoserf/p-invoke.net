## CM_Get_Device_ID_List_Size

```csharp
[DllImport("setupapi.dll", SetLastError = true)]
public static extern int CM_Get_Device_ID_List_Size(
   out int pulLen,
   string pDeviceID,
   uint ulFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/cfgmgr32/nf-cfgmgr32-cm_get_device_id_list_sizea)
