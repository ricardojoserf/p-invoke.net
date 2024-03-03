## SetupFindNextMatchLine

```csharp
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupFindNextMatchLine(
   IntPtr InfHandle,
   string Key,
   string Target,
   ref INFCONTEXT ContextIn,
   ref INFCONTEXT ContextOut
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupfindnextmatchlinew)
