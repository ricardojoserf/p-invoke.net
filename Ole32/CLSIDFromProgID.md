## CLSIDFromProgID

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CLSIDFromProgID(
   [MarshalAs(UnmanagedType.LPWStr)] string lpszProgID,
   out Guid pclsid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-clsidfromprogid)
