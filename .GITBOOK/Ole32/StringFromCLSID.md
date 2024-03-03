## StringFromCLSID

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StringFromCLSID(
   ref Guid rclsid,
   [MarshalAs(UnmanagedType.LPWStr)] out string lplpsz
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-stringfromclsid)
