## SetupDiBuildClassInfoList

```csharp
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiBuildClassInfoList(
   uint Flags,
   IntPtr ClassGuidList,
   uint ClassGuidListSize,
   ref uint RequiredSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdibuildclassinfolist)
