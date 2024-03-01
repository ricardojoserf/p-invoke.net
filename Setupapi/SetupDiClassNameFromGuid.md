## SetupDiClassNameFromGuid

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiClassNameFromGuid(
   ref Guid ClassGuid,
   StringBuilder ClassName,
   uint ClassNameSize,
   ref uint RequiredSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdiclassnamefromguidw)
