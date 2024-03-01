## SetupFindNextLine

```
[DllImport("setupapi.dll", SetLastError = true)]
public static extern bool SetupFindNextLine(
   IntPtr InfHandle,
   ref INFCONTEXT ContextIn,
   ref INFCONTEXT ContextOut
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupfindnextlinew)
