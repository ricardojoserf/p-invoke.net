## SetupDiBuildClassInfoList

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiBuildClassInfoList(
   uint Flags,
   IntPtr ClassGuidList,
   uint ClassGuidListSize,
   ref uint RequiredSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdibuildclassinfolistw)
