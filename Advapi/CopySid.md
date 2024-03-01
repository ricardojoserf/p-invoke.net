## CopySid

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CopySid(
   uint nDestinationSidLength,
   IntPtr pDestinationSid,
   IntPtr pSourceSid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-copysida)
