## SetupDiClassGuidsFromName

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiClassGuidsFromName(
   string ClassName,
   ref Guid ClassGuidList,
   uint ClassGuidListSize,
   ref uint RequiredSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdiclassguidsfromnamew)
