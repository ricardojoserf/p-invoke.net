## SetupCopyOEMInf

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupCopyOEMInf(
   string SourceInfFileName,
   string OEMSourceMediaLocation,
   OemSourceMediaType OEMSourceMediaType,
   OemCopyStyle CopyStyle,
   StringBuilder DestinationInfFileName,
   int DestinationInfFileNameSize,
   ref int RequiredSize,
   out IntPtr DestinationInfFileNameComponent
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupcopyoeminfw)
