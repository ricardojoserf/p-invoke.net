## SetupDiOpenClassRegKeyEx

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr SetupDiOpenClassRegKeyEx(
   ref Guid ClassGuid,
   uint samDesired,
   uint Flags,
   string MachineName,
   IntPtr Reserved,
   IntPtr ClassKey,
   IntPtr Reserved2
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdiopenclassregkeyexw)
