## SetupUninstallOEMInf

```csharp
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupUninstallOEMInf(
   string InfFileName,
   uint Flags,
   IntPtr Reserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupuninstalloeminfw)
