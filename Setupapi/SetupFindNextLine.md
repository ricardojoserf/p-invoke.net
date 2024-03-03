## SetupFindNextLine

```csharp
[DllImport("setupapi.dll", SetLastError = true)]
public static extern bool SetupFindNextLine(
   IntPtr InfHandle,
   ref INFCONTEXT ContextIn,
   ref INFCONTEXT ContextOut
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupfindnextline)
