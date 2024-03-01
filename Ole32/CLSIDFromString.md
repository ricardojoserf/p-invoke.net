## CLSIDFromString

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CLSIDFromString(
   [MarshalAs(
   UnmanagedType.LPWStr)] string lpsz,
   out Guid pclsid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-clsidfromstring)
