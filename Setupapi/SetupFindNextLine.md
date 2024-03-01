## SetupFindNextLine

```
[DllImport("setupapi.dll", SetLastError = true)]
public static extern bool SetupFindNextLine(
   IntPtr InfHandle,
   ref INFCONTEXT ContextIn,
   ref INFCONTEXT ContextOut
);
```

Microsoft documentation: (TODO)
