## SetupFindFirstLine

```csharp
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr SetupFindFirstLine(
   IntPtr InfHandle,
   string Section,
   string Key,
   ref INFCONTEXT Context
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupfindfirstlinew)
