## CM_Get_Sibling

```csharp
[DllImport("setupapi.dll", SetLastError = true)]
public static extern int CM_Get_Sibling(
   out uint pdnDevInst,
   uint dnDevInst,
   uint ulFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/cfgmgr32/nf-cfgmgr32-cm_get_sibling)
