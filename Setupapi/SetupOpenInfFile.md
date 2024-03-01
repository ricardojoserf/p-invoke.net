## SetupOpenInfFile

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr SetupOpenInfFile(
   string InfName,
   string InfClass,
   uint InfStyle,
   out uint ErrorLine
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupopeninffilew)
